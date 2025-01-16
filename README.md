# Off-by-One Error in Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The bug occurs because the loop condition `i <= arr.length` should be `i < arr.length` to prevent accessing the array beyond its bounds.  The solution shows how to correct this error by using the appropriate loop condition.  This leads to a better and more robust code.