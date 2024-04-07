# Exercise 6 - Nested Ternary Operator Challenge

**Task Description:**

Write a JavaScript function that uses nested ternary operators to classify a given day as "Weekday", "Weekend", or "Invalid" based on the day name provided. Further, it should classify the day as "Workday" or "Day Off" if it's a valid weekday or weekend, respectively.

**Objective:**

This exercise is designed to push the limits of ternary operator usage by incorporating nested conditions and string comparison to perform complex decision-making.

**Example Input:**

- "Monday"
- "Sunday"
- "Funday"

**Example Output:**

- "Monday is a Weekday and it's a Workday."
- "Sunday is a Weekend and it's a Day Off."
- "Funday is Invalid."

**Instructions:**

1. Define a variable for the day name.
2. Use nested ternary operators to first classify the day as "Weekday", "Weekend", or "Invalid".
3. For "Weekday" and "Weekend", further classify and append "Workday" or "Day Off", respectively.
4. Display the full classification message using `console.log()`.

**Hints:**

- Start with a broad ternary operator to categorize the day as "Weekday", "Weekend", or "Invalid".
- Within each case, nest another ternary operator to determine if it's a "Workday" or "Day Off".
- Remember to account for case sensitivity when comparing day names.
