# Exercise 3 - Check for Prime

**Task Description**

Develop a JavaScript function named `isPrime` that determines whether a given number is a prime number. Implement the function with an efficient algorithm to minimize the number of iterations.

**Objective**

This task aims to enhance your understanding of mathematical concepts in programming and improve your ability to implement efficient algorithms in JavaScript.

**Requirements**

- The function should accept a numerical input and return a boolean indicating whether the number is prime.
- Consider edge cases such as negative numbers, 0, and 1, which are not prime.

**Example Usage**

```javascript
console.log(isPrime(7)); // Expected Output: true
console.log(isPrime(10)); // Expected Output: false
```

**Instructions**

- Initialize a loop that starts from 2 (the smallest prime number) and checks divisibility up to the square root of the input number.
- If the input number is divisible by any number other than 1 and itself, return false.
- If the loop completes without finding any divisors, return true.
