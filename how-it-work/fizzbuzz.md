### FizzBuzz

[Back Home](../README.md)

The `fizzBuzz` function is a simple JavaScript program that performs the classic FizzBuzz problem. The FizzBuzz problem requires you to print numbers from 1 to a specified `n` (inclusive) with the following rules:

1. If a number is divisible by 3, print "Fizz" instead of the number.
2. If a number is divisible by 5, print "Buzz" instead of the number.
3. If a number is divisible by both 3 and 5, print "FizzBuzz" instead of the number.
4. Otherwise, print the number itself.

Here's how the `fizzBuzz` function works step by step:

1. It takes one argument, `n`, which represents the range of numbers to apply the FizzBuzz logic to.

2. It uses a `for` loop to iterate from `1` to `n`, inclusive. During each iteration, it examines the current number, represented by the variable `i`.

3. It uses conditional statements (`if`, `else if`, and `else`) to check the divisibility of `i` by 3 and 5 and prints the corresponding output based on the rules mentioned above.

   - If `i` is divisible by both 3 and 5, it prints "FizzBuzz."
   - If `i` is divisible by 3 (but not 5), it prints "Fizz."
   - If `i` is divisible by 5 (but not 3), it prints "Buzz."
   - If none of the above conditions are met, it prints the current number `i`.

4. The loop continues until `i` reaches the value of `n`, and the function prints the appropriate output for each number in the range.

When you call the `fizzBuzz` function with a specific value of `n`, it follows these rules for each number from 1 to `n` and prints the results accordingly. This is a common programming exercise used to test basic programming logic and control flow.
