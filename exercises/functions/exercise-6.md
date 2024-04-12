# Exercise 6 - Array Filter Function

**Task Description**

Create a JavaScript function named `customFilter` that mimics the behavior of the Array.prototype.filter method. This function should take an array and a callback function as arguments and return a new array containing elements that pass the test implemented by the callback function.

**Objective**

This exercise aims to deepen your understanding of array manipulation and callback functions in JavaScript.

**Requirements**

- The function should not use the built-in `Array.prototype.filter` method.
- It should correctly filter elements based on the callback's return value.

**Example Usage**

```js
const numbers = [1, 2, 3, 4, 5, 6];
const isEven = (num) => num % 2 === 0;
console.log(customFilter(numbers, isEven)); // Expected Output: [2, 4, 6]
```

**Instructions**

- Implement the function using a loop to iterate through the array.
- Apply the callback to each element to determine if it should be included in the result array.

**Hints**

- Initialize an empty array to store the results.
- Use the callback function to check each element; if the callback returns true, push the element to the result array.
