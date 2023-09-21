### Fibonacci Sequence

[Back Home](../README.md)

The `fibonacci` function you provided uses recursion to calculate Fibonacci numbers. Here's how it works step by step:

1. The function `fibonacci(n)` takes an integer `n` as its argument, representing the index of the Fibonacci number to be calculated.

2. The function checks if `n` is less than or equal to 1 with the condition `if (n <= 1)`. If `n` is 0 or 1, it returns `n` immediately because the Fibonacci sequence starts with 0 and 1, and these are the base cases.

3. If `n` is greater than 1, it proceeds to calculate the Fibonacci number for `n`. To do this, it calls itself recursively twice:

   - `fibonacci(n - 1)` calculates the (n-1)th Fibonacci number.
   - `fibonacci(n - 2)` calculates the (n-2)nd Fibonacci number.

4. The results of these two recursive calls are then added together (`fibonacci(n - 1) + fibonacci(n - 2)`), which gives the Fibonacci number for `n`.

5. The function continues to recursively call itself with decreasing values of `n` until it reaches the base cases (n <= 1), at which point it starts returning values back up the call stack.

Here's an example of how the function works with `fibonacci(5)`:

- `fibonacci(5)` calls `fibonacci(4)` and `fibonacci(3)`.
  - `fibonacci(4)` calls `fibonacci(3)` and `fibonacci(2)`.
    - `fibonacci(3)` calls `fibonacci(2)` and `fibonacci(1)`.
      - `fibonacci(2)` returns 1 (base case).
      - `fibonacci(1)` returns 1 (base case).
    - `fibonacci(3)` returns 2 (`fibonacci(2)` + `fibonacci(1)`).
    - `fibonacci(4)` returns 3 (`fibonacci(3)` + `fibonacci(2)`).
  - `fibonacci(5)` returns 5 (`fibonacci(4)` + `fibonacci(3)`).

So, `fibonacci(5)` returns 5, which is the 5th Fibonacci number. This process continues recursively, calculating Fibonacci numbers for larger values of `n` by breaking them down into smaller Fibonacci number calculations until it reaches the base cases.

---

The output of `55` for `n = 10` is indeed the correct 10th Fibonacci number. Here's how it's calculated step by step using the `fibonacci` function:

1. `fibonacci(10)` calls `fibonacci(9)` and `fibonacci(8)`.

2. `fibonacci(9)` calls `fibonacci(8)` and `fibonacci(7)`.

3. This recursive process continues until it reaches the base cases:

   - `fibonacci(2)` returns 1 (base case).
   - `fibonacci(1)` returns 1 (base case).

4. Now, the function starts returning values back up the call stack:

   - `fibonacci(3)` returns `fibonacci(2) + fibonacci(1)` = 1 + 1 = 2.
   - `fibonacci(4)` returns `fibonacci(3) + fibonacci(2)` = 2 + 1 = 3.
   - `fibonacci(5)` returns `fibonacci(4) + fibonacci(3)` = 3 + 2 = 5.
   - `fibonacci(6)` returns `fibonacci(5) + fibonacci(4)` = 5 + 3 = 8.
   - `fibonacci(7)` returns `fibonacci(6) + fibonacci(5)` = 8 + 5 = 13.
   - `fibonacci(8)` returns `fibonacci(7) + fibonacci(6)` = 13 + 8 = 21.
   - `fibonacci(9)` returns `fibonacci(8) + fibonacci(7)` = 21 + 13 = 34.

5. Finally, `fibonacci(10)` returns `fibonacci(9) + fibonacci(8)` = 34 + 21 = 55.

So, the 10th Fibonacci number is indeed 55, which is why the output of `fibonacci(10)` is 55.
