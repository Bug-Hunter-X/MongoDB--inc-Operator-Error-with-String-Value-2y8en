# MongoDB $inc Operator Error with String Value
This repository demonstrates a common error when using the `$inc` operator in MongoDB: attempting to increment a field with a string value.

## Bug Description
The `$inc` operator in MongoDB is used to increment a numerical field by a specified value.  However, if you provide a string value to `$inc`, MongoDB will throw an error because it cannot perform a numerical increment on a string.

## Bug Solution
The solution is straightforward: ensure that the value being incremented is a number.  The corrected code is shown in the `bugSolution.js` file.