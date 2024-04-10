# Exercise 4 - Fibonacci Sequence

**Task Description**

Create a JavaScript function named `fibonacci` that generates the Fibonacci sequence up to a given number `n`. The Fibonacci sequence is characterized by each number being the sum of the two preceding ones, starting from 0 and 1.

**Objective**

This exercise aims to improve your skills in implementing algorithms and understanding sequence generation in JavaScript.

**Requirements**

- The function should accept a numerical input `n` and return an array containing the Fibonacci sequence up to the `n`th term.
- Ensure the function handles both small and large values of `n` efficiently.

**Example Usage**

```javascript
console.log(fibonacci(5)); // Expected Output: [0, 1, 1, 2, 3, 5]
console.log(fibonacci(10)); // Expected Output: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55]
```

**Instructions**

- Initialize the sequence with the first two numbers, 0 and 1.
- Use a loop to iteratively calculate the next numbers in the sequence by adding the two previous numbers.
- Continue this process until you have generated n numbers in the sequence.

**Hints**

- Remember that the first two numbers of the Fibonacci sequence are always 0 and 1.
- For efficiency, especially with larger values of n, consider ways to minimize the computational overhead.
