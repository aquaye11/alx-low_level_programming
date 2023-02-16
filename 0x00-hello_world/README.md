#!/bin/bash
0-preprocessor writes a script that runs a C file through the preprocessor and save the result into another file where the C file name will be saved in the variable $CFILE and the output should be saved in the file c
1-compiler writes a script that compiles a C file but does not link and the C file name will be saved in the variable $CFILE where the output file should be named the same as the C file, but with the extension .o instead of .c
2-assembler writes a script that generates the assembly code of a C code and save it in an output file and the C file name will be saved in the variable $CFILE where the output file should be named the same as the C file, but with the extension .s instead of .c
3-name writes a script that compiles a C file and creates an executable named cisfun where the C file name will be saved in the variable $CFILE
