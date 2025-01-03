# TypeScript Type Mismatch Bug

This repository demonstrates a common type mismatch error in TypeScript. The `add` function is defined to accept two numbers, but the code attempts to call it with a string and a number, resulting in a type error.

## Bug

The bug is present in `bug.ts`. It occurs because TypeScript's type system prevents incompatible operations.

## Solution

The solution, provided in `bugSolution.ts`, addresses the bug by ensuring that the arguments passed to the `add` function are of the correct type.

This example highlights the importance of proper type handling in TypeScript to avoid runtime errors.