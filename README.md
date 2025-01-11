# MongoDB $inc operator error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.
The error occurs when providing a string value to the `$inc` operator instead of a number.  The `$inc` operator requires a numerical value to increment a field.  Attempting to increment with a string results in an error.

The solution shows the correct usage, which involves using a numerical value. 
