# Python Programming Style Guide

[![Buy Me A Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://tinyurl.com/2h9aktmd) &nbsp; [![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://tinyurl.com/d4xnrptz) &nbsp; [![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://tinyurl.com/mr22naua) &nbsp; [![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3)

This style guide provides guidelines for writing Python code that is readable, maintainable, and consistent.

## Table of Contents
1. [Introduction](#introduction)
2. [Naming Conventions](#naming-conventions)
3. [Code Formatting](#code-formatting)
4. [Comments](#comments)
5. [Function and Method Definitions](#function-and-method-definitions)
6. [Imports](#imports)
7. [Exceptions](#exceptions)
8. [Whitespace](#whitespace)
9. [Miscellaneous](#miscellaneous)

## Naming Conventions
- Use `lowercase_with_underscores` for variable and function names.
- Use `CAPITALIZED_WITH_UNDERSCORES` for constants.
- Use `CamelCase` for class names.
- Avoid single-character names, unless they have a well-defined meaning.
- Avoid using reserved keywords as names.

## Code Formatting
- Use 4 spaces for indentation (avoid tabs).
- Limit lines to a maximum of 79 characters.
- Use a single space around operators and after commas.
- Use blank lines to separate logical sections of code.

## Comments
- Use comments to explain non-obvious code behavior.
- Write self-explanatory code that reduces the need for comments.
- Use complete sentences and proper grammar in comments.

## Function and Method Definitions
- Use descriptive names for functions and methods.
- Add a docstring to describe the purpose, inputs, and outputs of the function.
- Limit the number of arguments to keep functions concise.

## Imports
- Import modules on separate lines, grouped in the following order:
    1. Standard library imports.
    2. Third-party library imports.
    3. Local application imports.
- Avoid using wildcard imports (`from module import *`).

## Exceptions
- Catch specific exceptions instead of using a bare `except` clause.
- Avoid catching and swallowing exceptions silently.

## Whitespace
- Use a single blank line to separate logical sections of code.
- Use blank lines sparingly within functions to improve readability.
- Avoid excessive whitespace at the end of lines or empty lines at the end of files.

## Miscellaneous
- Be consistent with the style guide within a project.
- Write code that is easy to understand and maintain.
- Refactor code to improve readability and eliminate code duplication.

---

This style guide is inspired by the [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide with a few additional recommendations.
