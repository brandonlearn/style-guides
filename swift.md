# Swift Style Guide

[![Buy Me A Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://tinyurl.com/2h9aktmd) &nbsp; [![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://tinyurl.com/d4xnrptz) &nbsp; [![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://tinyurl.com/mr22naua) &nbsp; [![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3)

## Table of Contents
1. [Naming Conventions](#naming-conventions)
2. [Formatting](#formatting)
3. [Comments](#comments)
4. [Control Flow](#control-flow)
5. [Error Handling](#error-handling)

## Naming Conventions
- Use descriptive names for variables, functions, and types.
- Follow camel case for variable and function names (e.g., `myVariable`, `calculateResult()`).
- Use uppercase camel case for type names (e.g., `MyClass`, `PersonModel`).
- Prefix class properties with `self` to differentiate from method arguments and local variables.

## Formatting
- Indent using 4 spaces.
- Use spaces around operators and after commas.
- Place opening braces on the same line as the associated statement or declaration.
- Place `else` statements on the same line as the closing brace of the previous `if` statement.

## Comments
- Use `//` for single-line comments and `/* ... */` for multi-line comments.
- Write descriptive comments that explain the purpose of the code.
- Avoid excessive commenting for obvious or self-explanatory code.

## Control Flow
- Use `if` and `guard` statements for conditions and early exits.
- Prefer the `for-in` loop for iterating over collections.
- Use `switch` statements for multiple conditions with associated values.
- Use `defer` to clean up resources or perform actions before exiting a scope.

## Error Handling
- Use Swift's `try-catch` mechanism for handling errors.
- Avoid using exceptions for flow control.
- Create custom error types for specific error cases.
- Use `throws` in function declarations to indicate that it can throw an error.

