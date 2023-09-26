### Factorial

[Back Home](../README.md)

The `factorial` function you provided is a recursive function that calculates the factorial of a number. Let's break down how it works step by step:

1. **Base Case**:

   - The function begins by checking if `n` is equal to `0`. If it is, it immediately returns `1`. This is called the base case. In mathematics, `0!` (0 factorial) is defined to be `1`.

2. **Recursive Step**:

   - If `n` is not `0`, the function proceeds to the recursive step. It calculates `n * factorial(n - 1)`. This means it multiplies `n` by the result of calling `factorial` with `n - 1`.

   - For example,if called again with `n` equal to 4, and it calculates `4 * factorial(3)` and `factorial(5)`, it will calculate `5 * factorial(4)`. This triggers another call to `factorial` with `n - 1`, and so on.

3. **Recursive Calls**:

   - The function keeps calling itself with decreasing values of `n` until it reaches the base case where `n` is `0`. At this point, the function starts returning values back up the chain of recursive calls.
   - When `n` is 0, it starts returning values back up the chain. So, `factorial(0)` returns 1, `factorial(1)` returns 1, `factorial(2)` returns 2, `factorial(3)` returns 6, `factorial(4)` returns 24, and finally, `factorial(5)` returns 120.

4. **Returning Values**:

   - Once the base case is reached, the function starts returning values back through all the recursive calls.

   - For example, if you called `factorial(5)`, it would go through the following steps:

     ```
     factorial(5) => 5 * factorial(4) => 5 * (4 * factorial(3)) => 5 * (4 * (3 * factorial(2))) => 5 * (4 * (3 * (2 * factorial(1)))) => 5 * (4 * (3 * (2 * (1 * factorial(0))))) => 5 * (4 * (3 * (2 * (1 * 1))))
     ```

   - The final value, `5 * (4 * (3 * (2 * (1 * 1))))`, is returned as the result.

In summary, the function breaks down the problem of calculating `n!` into smaller sub problems by recursively calculating `(n-1)!`, `(n-2)!`, and so on until it reaches the base case of `0!`, which is defined as 1. It then combines the results of these smaller sub problems to compute the factorial of the original number `n`. This is a classic example of recursion in action.

The `factorial` function is defined using recursion, which is a programming technique where a function calls itself in order to solve a problem. Let's break down how this specific `factorial` function works:

The output of 120 for `factorial(5)` is correct because 5 factorial (`5!`) is equal to 120 according to the mathematical definition of factorial.

Here's the breakdown of how `factorial(5)` is calculated:

```javascript
factorial(5) = 5 * factorial(4)
             = 5 * (4 * factorial(3))
             = 5 * (4 * (3 * factorial(2)))
             = 5 * (4 * (3 * (2 * factorial(1))))
             = 5 * (4 * (3 * (2 * 1))) // factorial(1) is 1 by definition
             = 5 * (4 * (3 * 2))
             = 5 * (4 * 6)
             = 5 * 24
             = 120
```

So, `factorial(5)` is indeed equal to 120. The factorial of a positive integer `n` is the product of all positive integers from 1 to `n`, inclusive. In this case, `5!` is calculated as 5 _ 4 _ 3 _ 2 _ 1, which equals 120.
