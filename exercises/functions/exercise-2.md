# Exercise 2 - Reverse a Number

**Task Description**

Create a JavaScript function named `reverseNumber` that reverses the digits of a given number. You need to implement two versions of this function:

- **Version 1**: Using higher-order functions.
- **Version 2**: Using loops, without higher-order functions.

**Objective**

This exercise is designed to improve your skills in number manipulation, understanding and using higher-order functions, and mastering loops in JavaScript.

**Requirements**

- The function should accept a numerical input and return a numerical output with its digits in reverse order.
- Ensure that the function can handle various types of inputs, such as negative numbers and integers.

**Example Usage**

```javascript
console.log(reverseNumber(12345)); // Expected Output: 54321
console.log(reverseNumber(-67890)); // Expected Output: -9876
```

**Instructions**

1. Version 1 - Higher-Order Functions:

   - Convert the number to a string to manipulate its characters.
   - Use string and array higher-order functions to reverse the order of the digits.
   - Convert the reversed string back to a number and return it.

2. Version 2 - Loops:

   - Initialize a variable to hold the reversed number, starting from 0.
   - Use a loop to extract each digit from the original number, starting from the last digit.
   - In each iteration, update the reversed number variable by appending the extracted digit, adjusting for place value

Ensure that both versions of your function pass the example usage tests.

**Hints**

- Consider the toString(), split(), reverse(), join(), and parseInt() functions for Version 1.
- For Version 2, consider using % (modulo) to extract the last digit of the number and Math.floor() or division to remove the last digit from the number in each iteration. Update the reversed number by multiplying the current reversed number by 10 and adding the extracted digit.
