# Type Error in TypeScript

This repository demonstrates a common type error in TypeScript that arises when passing an array to a function expecting a string argument. The code attempts to pass a string array to the `greeter` function, which is defined to accept a single string. TypeScript correctly flags this as a type error.

The solution demonstrates how to correctly handle this situation, ensuring type safety and correct program behavior.  We modify the `greeter` function to accept either a single string or an array of strings, appropriately handling both cases.