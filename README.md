# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The error occurs because the loop condition is incorrect, leading to an `ArrayIndexOutOfBoundsException`.

## Bug Description

The Java code iterates over an array using a `for` loop. However, the loop condition `i <= arr.length` is incorrect and causes the code to try to access an element beyond the array's bounds resulting in an `ArrayIndexOutOfBoundsException`.

## Bug Solution

The solution is to change the loop condition to `i < arr.length`. This ensures that the loop iterates only within the valid bounds of the array.
