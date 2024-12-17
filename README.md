# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value.  However, if a string value is provided instead of a number, the operation will fail.

## Bug
The bug lies in the incorrect usage of the `$inc` operator with a string value. This results in an error because the `$inc` operator expects a numeric value.

## Solution
The solution involves providing a numeric value to the `$inc` operator, correcting the data type and ensuring the update operation works as expected.

## How to reproduce
1. Clone this repository.
2. Run the `bug.js` script.
3. Observe the error that occurs.