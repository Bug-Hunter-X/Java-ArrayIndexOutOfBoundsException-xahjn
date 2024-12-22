# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The `bug.java` file contains code that attempts to access an array element outside its valid index range.  The `bugSolution.java` file shows how to fix this error.

## Bug Description

The bug occurs because the code tries to access `arr[5]` in an array that only has indices 0-4.  This leads to an `ArrayIndexOutOfBoundsException` at runtime.

## Solution

The solution involves ensuring that all array accesses are within the valid index range (0 to array.length - 1).  The corrected code in `bugSolution.java` checks the index before accessing the array element.