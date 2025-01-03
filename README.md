# MongoDB $inc Operator with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment a numerical value by a specified amount, however if a string is provided, it will not work as expected.

## Bug
The `bug.js` file shows an example of this error. The `$inc` operator is used with a string value for the increment, resulting in an unexpected update rather than the expected numerical increment.

## Solution
The `bugSolution.js` file provides the corrected code.  The string value has been corrected to a number, ensuring the `$inc` operator functions correctly.