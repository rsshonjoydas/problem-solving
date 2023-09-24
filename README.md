[![Facebook-Page][facebook-shield]][facebook-url]
[![Twitter][twitter-shield]][twitter-url]
[![Instagram][instagram-shield]][instagram-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<p align="center">
  <h3 align="center">Problem Solving</h3>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Fibonacci Sequence](#fibonacci-sequence)
- [Reverse a String](#reverse-a-string)
- [Contact](#contact)

<!-- Fibonacci Sequence -->

## Fibonacci Sequence

- Problem: Write a function to generate the nth Fibonacci number.
- [How it works](./how-it-work/fibonacci.md)
- Solution:

---

#### JavaScript Section

```javascript
function fibonacci(n) {
  if (n <= 1) return n;
  return fibonacci(n - 1) + fibonacci(n - 2);
}
```

[Try it Yourself](https://replit.com/@rsshonjoydas/Fibonacci-Sequence-JavaScript)

#### Python Section

```python
def fibonacci(n):
  if n <= 1:
    return n
  return fibonacci(n - 1) + fibonacci(n - 2)
```

[Try it Yourself](https://replit.com/@rsshonjoydas/Fibonacci-Sequence-Python)

<!-- Reverse a String -->

## Reverse a String

- Problem: Reverse a given string.
- Solution:

---

#### JavaScript Section

```javascript
function reverseString(str) {
  return str.split('').reverse().join('');
}
```

[Try it Yourself](https://replit.com/@rsshonjoydas/Reverse-a-String-JavaScript)

#### Python Section

```python
def reverse_string(s):
  return ''.join(reversed(s))
```

[Try it Yourself](https://replit.com/@rsshonjoydas/Reverse-a-String-Python)

---

<!-- CONTACT -->

## Contact

Shonjoy Das - [rsshonjoydas@gmail.com](mailto:rsshonjoydas@gmail.com)

<!-- MARKDOWN LINKS & IMAGES -->

[facebook-shield]: https://img.shields.io/badge/-Facebook-black.svg?style=flat-square&logo=facebook&color=555&logoColor
[facebook-url]: https://facebook.com/rsshonjoydas
[twitter-shield]: https://img.shields.io/badge/-Facebook-black.svg?style=flat-square&logo=twitter&color=555&logoColor
[twitter-url]: https://twitter.com/rsshonjoydas
[instagram-shield]: https://img.shields.io/badge/-Instagram-black.svg?style=flat-square&logo=instagram&color=555&logoColor
[instagram-url]: https://instagram.com/rsshonjoydas
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB
[linkedin-url]: https://linkedin.com/in/rsshonjoydas