# JavaScript Loose Typing Bug

This repository demonstrates a common error in JavaScript caused by its loose typing system.  The bug arises from using the + operator with a mix of numbers and strings, resulting in string concatenation instead of mathematical addition. This often leads to unexpected results.

## Bug Description:
The `myFunction` adds two values.  However, if one value is a string, the + operator will concatenate the string, instead of performing numerical addition.  This issue commonly occurs when dealing with user input or data received from external sources.

## Solution:
The solution involves explicitly converting the operands to numbers before performing the addition operation.  This ensures that the expected mathematical operation takes place, preventing unexpected string concatenation.

## How to reproduce the bug:
1. Clone this repository.
2. Run the `bug.js` file using a JavaScript interpreter (e.g., Node.js). 
3. Observe the unexpected output.