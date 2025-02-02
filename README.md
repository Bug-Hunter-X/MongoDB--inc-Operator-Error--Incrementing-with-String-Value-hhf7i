# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation.
The `$inc` operator is used to increment a numerical value by a specified amount.  However, in this case, a string ('1') is used instead of a number (1), resulting in an unexpected outcome.
The solution corrects this error by using the correct numerical value for the increment.