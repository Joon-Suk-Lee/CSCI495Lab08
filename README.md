# CSCI495Lab08

Finish writing the "calculateSubTotal" function.

- The function takes a nested integer array (an array of integer arrays) as an input.
(e.g. [[1,2,3,4], [2,3], [ ], [2, 3, 3]] )

- The function returns an integer array that holds the subtotals of the inner input arrays.
For instance, if you feed [[1], [1,1], [1,1,1]] into the function, the function should return [1, 2, 3].

- You can assume that the input array will not have any errors.
- The inner array can be an empty array, [ ], in which case the subtotal for the empty array should be 0.

Sample Input and Output

[[11,11,22], [22], [], [1,2,3]] -> [44, 22, 0, 6]
