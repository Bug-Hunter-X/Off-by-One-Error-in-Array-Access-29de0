# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java. The code attempts to access an array element outside of its bounds, leading to an `ArrayIndexOutOfBoundsException`.

## Bug Description
The `for` loop iterates from `i = 0` to `i <= arr.length`.  The correct condition should be `i < arr.length` because array indices are zero-based.

## Solution
The solution corrects the loop condition to avoid the out-of-bounds access.