# Null Value Handling in Function foo

This repository demonstrates a common JavaScript bug related to the handling of null values as function arguments. The function `foo` does not explicitly handle the case where `a` or `b` are null, leading to potential errors or unexpected behavior.

## Bug Description
The function `foo` lacks proper null checks and fails to handle cases where one or both input parameters are null values.

## Solution
The improved version of function `foo` in `bugSolution.js` adds explicit null checks to ensure the function behaves gracefully even when null values are provided as input. The solution uses conditional statements to check for null values and either return a default value or handle them as appropriate.
