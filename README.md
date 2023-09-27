[![Facebook-Page][facebook-shield]][facebook-url]
[![Twitter][twitter-shield]][twitter-url]
[![Instagram][instagram-shield]][instagram-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<p align="center">
  <h3 align="center">Problem Solving</h3>
</p>

---

1. **Fibonacci Sequence**:

   - Problem: Write a function to generate the nth Fibonacci number.
   - [How it works](./how-it-work/fibonacci.md)
   - Solution:

     > [JavaScript](https://replit.com/@rsshonjoydas/Fibonacci-Sequence-JavaScript)

     ```javascript
     function fibonacci(n) {
       if (n <= 1) return n;
       return fibonacci(n - 1) + fibonacci(n - 2);
     }
     ```

     > [Python](https://replit.com/@rsshonjoydas/Fibonacci-Sequence-Python)

     ```python
     def fibonacci(n):
       if n <= 1:
         return n
       return fibonacci(n - 1) + fibonacci(n - 2)
     ```

2. **Reverse a String**:

   - Problem: Reverse a given string.
   - Solution:

     > [JavaScript](https://replit.com/@rsshonjoydas/Reverse-a-String-JavaScript)

     ```javascript
     function reverseString(str) {
       return str.split('').reverse().join('');
     }
     ```

     > [Python](https://replit.com/@rsshonjoydas/Reverse-a-String-Python)

     ```python
     def reverse_string(s):
       return ''.join(reversed(s))
     ```

3. **Factorial**:

   - Problem: Write a function to calculate the factorial of a number.
   - [How it works](./how-it-work/factorial.md)
   - Solution:

     > [JavaScript](https://replit.com/@rsshonjoydas/Factorial-JavaScript)

     ```javascript
     function factorial(n) {
       if (n === 0) return 1;
       return n * factorial(n - 1);
     }
     ```

     > [Python](https://replit.com/@rsshonjoydas/Factorial-Python)

     ```python
     def factorial(n):
      if n == 0:
        return 1
      return n * factorial(n - 1)
     ```

4. **Palindrome**:

   - Problem: Check if a given string is a palindrome (reads the same forwards and backwards).
   - [How it works](./how-it-work/palindrome.md)
   - Solution:

     > [JavaScript](https://replit.com/@rsshonjoydas/Palindrome-JavaScript)

     ```javascript
     function isPalindrome(str) {
       return str === str.split('').reverse().join('');
     }
     ```

     > [Python](https://replit.com/@rsshonjoydas/Palindrome-Python)

     ```python
     def is_palindrome(s):
      return s == ''.join(reversed(s))
     ```

5. **Find the Largest Number**:

   - Problem: Write a function to find the largest number in an array.
   - Solution:
     > [JavaScript](https://replit.com/@rsshonjoydas/Find-the-Largest-Number-JavaScript)
     ```javascript
     function findLargest(arr) {
       return Math.max(...arr);
     }
     ```
     > [Python](https://replit.com/@rsshonjoydas/Find-the-Largest-Number-Python)
     ```python
     def find_largest(arr):
      return max(arr)
     ```

6. **Remove Duplicates**:
   - Problem: Remove duplicates from an array.
   - Solution:
     > [JavaScript](https://replit.com/@rsshonjoydas/Remove-Duplicates-JavaScript)
     ```javascript
     function removeDuplicates(arr) {
       return [...new Set(arr)];
     }
     ```
     > [Python](https://replit.com/@rsshonjoydas/Remove-Duplicates-Python)
     ```python
     def remove_duplicates(arr):
      return list(set(arr))
     ```

<!-- CONTACT -->

## Contact

Shonjoy Das - [rsshonjoydas@gmail.com](mailto:rsshonjoydas@gmail.com)

<!-- MARKDOWN LINKS & IMAGES -->

[facebook-shield]: https://img.shields.io/badge/-Facebook-black.svg?style=flat-square&logo=facebook&color=555&logoColor
[facebook-url]: https://facebook.com/rsshonjoydas
[twitter-shield]: https://img.shields.io/badge/-Twitter-black.svg?style=flat-square&logo=twitter&color=555&logoColor
[twitter-url]: https://twitter.com/rsshonjoydas
[instagram-shield]: https://img.shields.io/badge/-Instagram-black.svg?style=flat-square&logo=instagram&color=555&logoColor
[instagram-url]: https://instagram.com/rsshonjoydas
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB
[linkedin-url]: https://linkedin.com/in/rsshonjoydas
