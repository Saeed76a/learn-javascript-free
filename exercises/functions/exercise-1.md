# Exercise 1 - Palindrome Checker

**Task Description:**

Implement a JavaScript function named `isPalindrome` that takes a single string argument and returns `true` if the string is a palindrome and `false` otherwise. A palindrome is defined as a word, phrase, number, or other sequences of characters that reads the same forward and backward (ignoring spaces, punctuation, and capitalization).

**Objective:**

The goal of this exercise is to practice string manipulation, conditionals, and loops in JavaScript. You'll need to consider how to handle case sensitivity and non-alphanumeric characters to accurately determine if the input string is a palindrome.

**Requirements:**

- The function should be case-insensitive. For example, `isPalindrome("Noon")` should return `true`.
- The function should ignore all non-alphanumeric characters. For example, `isPalindrome("A man, a plan, a canal, Panama!")` should return `true`.

**Example Usage:**

```javascript
console.log(isPalindrome("noon")); // true
console.log(isPalindrome("Hello")); // false
console.log(isPalindrome("A Santa at NASA")); // true
console.log(isPalindrome("Was it a car or a cat I saw?")); // true
```

**Instructions:**

1. Define a function isPalindrome that accepts a string argument.
2. Normalize the string by converting it to the same case and removing non-alphanumeric characters.
3. Check if the normalized string reads the same forward and backward.
4. Return true if it is a palindrome and false otherwise.

**Hints:**

- You might find string methods such as toLowerCase(), replace(), and array methods like split(), reverse(), and join() useful for this task.
- Consider using a regular expression to strip non-alphanumeric characters from the string.
