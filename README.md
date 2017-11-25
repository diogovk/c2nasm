
# C2NASM

Uses gcc and objconv to convert a C program to nasm.

To use it, give execution permission to c2nasm.sh and then:

```
./c2nasm.sh <sourcefile.c>
```

The result will be a .nasm file with the nasm, and a .run file which is the executable.

Note that you might get a better nasm output by tunning the optimization parameter in gcc (`-O0` for no optimization, `-O3` to optimize as much as possible).



Based on the question:
http://stackoverflow.com/questions/20737947/how-to-generate-a-nasm-compilable-assembly-code-from-c-source-code-on-linux/
