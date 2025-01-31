# Uncommon C Pointer Bug: Unexpected Behavior with Simple Pointer Arithmetic

This repository demonstrates a subtle yet important bug related to pointer arithmetic and memory management in C.  The bug involves modifying a value via a pointer. While the presented example is simple, the same issues can manifest in far more complex scenarios and lead to hard-to-detect bugs.

The `bug.c` file contains the code with the bug, which involves simple pointer arithmetic.  The `bugSolution.c` file provides a corrected version which illustrates how to avoid potential issues related to pointer arithmetic and memory management.   Understanding this bug can be crucial for writing robust and reliable C code.

## How to run the code:

1. Save the code files (`bug.c` and `bugSolution.c`) in separate .c files.
2. Compile the code using a C compiler (like GCC): 
   `gcc bug.c -o bug`
   `gcc bugSolution.c -o bugSolution`
3. Run the compiled executables: 
   `./bug`
   `./bugSolution`

The output of both programs will demonstrate the difference between the original buggy code and the corrected solution.