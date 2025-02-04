# C Pointer Modification Bug

This repository demonstrates a simple yet common bug in C programming involving pointer manipulation and unintended variable modification.

## Bug Description
The `bug.c` file contains a program that initializes an integer variable `x` and then modifies its value indirectly using a pointer.  The problem lies in the lack of understanding how pointer arithmetic and dereferencing can affect the original variable.

## How to Reproduce
1. Compile the code using a C compiler (e.g., GCC): `gcc bug.c -o bug`
2. Run the executable: `./bug`

The output will be unexpected because the value of `x` is altered through the pointer.

## Solution
The `bugSolution.c` file provides a corrected version of the code. The fix ensures proper pointer usage and avoids unintended side effects.