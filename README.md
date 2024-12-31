# Assembly Code Bug: Buffer Overflow and Null Pointer Dereference

This repository demonstrates a common error in assembly code: a potential buffer overflow and lack of null pointer checks.  The `bug.asm` file contains the vulnerable code snippet.  The `bugSolution.asm` file provides a corrected version with improved error handling and bounds checking.

## Vulnerable Code

The original code attempts to add two values and store the result. However, it lacks crucial checks to prevent buffer overflows and handle null pointers.

## Solution

The solution adds checks to ensure the memory addresses are valid and the addition doesn't exceed the buffer bounds.  This prevents overwriting memory and avoids segmentation faults.

This example highlights the importance of careful memory management and error handling in low-level programming.