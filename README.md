# Unexpected String Concatenation with + Operator in JavaScript
This repository demonstrates an uncommon bug in JavaScript related to the unexpected behavior of the + operator when used with strings and numbers.  The + operator in JavaScript will perform string concatenation if one of the operands is a string, rather than arithmetic addition. This can lead to unexpected results in calculations if not handled carefully.

## Bug Description
The bug arises from the implicit type coercion of the + operator. If either operand is a string, JavaScript treats the operation as string concatenation. This is different from many other programming languages where the behavior would typically result in a type error or automatic type conversion.

## How to reproduce
1. Clone this repository.
2. Run the JavaScript file `bug.js`. Observe the unexpected results.

## Solution
The solution demonstrates how to handle this situation correctly through explicit type conversions.
