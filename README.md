# MongoDB $inc Operator Error: Using String Instead of Number

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field in a document.  However, if you provide a string value to the `$inc` operator instead of a number, it may lead to unexpected results.

## The Bug
The bug occurs when a string value is passed to the `$inc` operator, causing incorrect updates.

## The Solution
Ensure that the value provided to the `$inc` operator is a number to avoid errors and ensure accurate incrementations.
