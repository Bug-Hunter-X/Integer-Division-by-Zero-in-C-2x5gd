# Integer Division by Zero in C
This repository demonstrates a common error in C programming: integer division by zero.  The `bug.c` file contains the problematic code. The `bugSolution.c` file provides a solution to prevent this error.

## Problem
Attempting to divide an integer by zero results in undefined behavior. This can lead to program crashes or unexpected results.

## Solution
The solution involves adding checks to prevent division by zero. One approach is to add a conditional statement to handle the case where the divisor is zero.