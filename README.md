# TypeScript Array to String Argument Error

This repository demonstrates a common TypeScript error: passing an array of strings to a function expecting a single string.

## Bug
The `greeter` function expects a single string argument.  However, the `user` variable is an array of strings.  This causes a type error.

## Solution
The solution involves either modifying the `greeter` function to accept an array or modifying the way the `user` variable is passed to the function.  The solution provided shows how to modify the `user` variable to pass a single string (or a string created by joining array elements).