# LEETCODE-Array-1550
Sure, let's go through a dry run of the `threeConsecutiveOdds` method with an example array to understand how it works.

Consider the input array: `[2, 6, 4, 1, 3, 5, 7]`

1. Initialize `count` to 0.
2. Iterate through each element in the array:

   - For `a = 2`: 
     - `2 % 2 == 1` is `false`.
     - `count` is reset to 0.
     - `count` is 0 (no three consecutive odd numbers so far).

   - For `a = 6`: 
     - `6 % 2 == 1` is `false`.
     - `count` is reset to 0.
     - `count` is 0 (no three consecutive odd numbers so far).

   - For `a = 4`: 
     - `4 % 2 == 1` is `false`.
     - `count` is reset to 0.
     - `count` is 0 (no three consecutive odd numbers so far).

   - For `a = 1`: 
     - `1 % 2 == 1` is `true`.
     - `count` is incremented to 1.
     - `count` is 1 (no three consecutive odd numbers so far).

   - For `a = 3`: 
     - `3 % 2 == 1` is `true`.
     - `count` is incremented to 2.
     - `count` is 2 (no three consecutive odd numbers so far).

   - For `a = 5`: 
     - `5 % 2 == 1` is `true`.
     - `count` is incremented to 3.
     - `count` is 3 (three consecutive odd numbers found).

3. Since `count` has reached 3, the method returns `true`.

The output for the input array `[2, 6, 4, 1, 3, 5, 7]` is `true` because there are three consecutive odd numbers (1, 3, 5) in the array.

The method correctly identifies whether there are three consecutive odd numbers in the given array.
