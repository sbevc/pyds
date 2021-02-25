# RECURSION

## 3 steps

1. Recursive case

Identify the recursive case. Given a problem, identify how to make a smaller instance
of the same problem.

For example, taking the factorial:

By definition: 
    a. n! = n * (n-1) * (n-2) * ... * 2 * 1
    b. (n-1)! = (n-1) * (n-1-1) * ... * 2 * 1 = (n-1) * (n-2) * ... * 2 * 1

So a can be rewritten as n! = n * (n-1)!, we have found the recursion!


2. Base case - stopping criteria

Identify where the recursion should stop. Following the example, the factorial is defined
only for positive numbers, and 0! is 1. So our base case is 0! = 1


3. Make sure our function stops for all given values

Make sure that all values make the function stop. In the factorial example, a check should
be made to be sure we are working with positive numbers.
