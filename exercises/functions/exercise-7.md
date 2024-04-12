# Exercise 7 - Sum of Digits

**Task Description**

Develop a JavaScript function named `sumDigits` that calculates the sum of all the digits in a given number.

**Objective**

This exercise is intended to enhance your ability to work with numbers and loops in JavaScript, reinforcing basic arithmetic operations and string manipulation.

**Requirements**

- The function should accept a numerical input and return the sum of its digits.
- Handle both positive and negative numbers appropriately.

**Example Usage**

```javascript
console.log(sumDigits(1234)); // Expected Output: 10
console.log(sumDigits(-1011)); // Expected Output: 3
```

**Instructions**

- Convert the number to a string to separate its digits.
- Iterate through the string, converting each character back to a number and summing them up.
- Consider how to handle negative numbers to ensure only the digits are summed, excluding the sign.

**Hints**

- Use the Math.abs() function to deal with negative numbers by converting them to positive.
- The split(), reduce(), and parseInt() functions might be useful in your implementation.
