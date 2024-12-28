# Off-by-One Error in Dart

This repository demonstrates a common off-by-one error in Dart when iterating over a list using a `for` loop.  The error occurs because the loop condition incorrectly includes the index equal to the length of the list, leading to an index out of bounds exception.  The solution demonstrates the correct way to iterate to avoid this error.

## Bug
The `bug.dart` file contains the erroneous code.  Running this code will result in an exception.

## Solution
The `bugSolution.dart` file provides the corrected code.