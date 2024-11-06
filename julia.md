# Julia Programming Style Guide

[![Buy Me A Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://tinyurl.com/2h9aktmd) &nbsp; [![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://tinyurl.com/d4xnrptz) &nbsp; [![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://tinyurl.com/mr22naua) &nbsp; [![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3)

## Naming Conventions

- Use lowercase letters and underscores for variable and function names: `my_variable`, `my_function`.
- Use descriptive and meaningful names.
- Avoid single-character variable names except for loop counters or generic iterators.
- Use camel case for struct and type names: `MyStruct`, `MyType`.
- Prefix boolean variables with "is" or "has": `is_ready`, `has_data`.

## Formatting

- Use 4 spaces for indentation (no tabs).
- Limit lines to 80 characters or less.
- Use spaces around operators and after commas, e.g., `x = 10 + y`, `my_function(arg1, arg2)`.
- Put a space after a comma in function arguments list.
- Use consistent and clear spacing for function calls and definitions.

## Comments

- Use comments to explain complex logic or clarify code.
- Write comments in complete sentences.
- Avoid obvious or redundant comments that merely repeat the code.

## Function and Macro Definitions

- Add a space between function or macro name and opening parenthesis: `my_function(arg1, arg2)`.
- Use lowercase for function and macro names.
- Separate arguments with commas and align them vertically if they span multiple lines.
- Use a single space after the comma separating a function argument.

## Control Flow

- Use `if`, `elseif`, and `else` for conditional statements.
- Put spaces around operators within conditions: `if x > 0`.
- Use `end` to close conditional blocks.
- Use `for` and `while` loops for iteration.
- Use `break` to exit loops prematurely.
- Use `continue` to skip the current iteration in a loop.

## Error Handling

- Use `try`, `catch`, and `finally` for error handling.
- Be specific with error types when catching exceptions.
- Avoid using `catchall` unless absolutely necessary.

## Documentation

- Use docstrings to document functions, macros, and types.
- Write clear and concise descriptions of the purpose, arguments, and return values.
- Include examples and provide explanations for complex behaviors.
- Use Markdown formatting in docstrings for formatting and readability.

## Testing

- Write tests for your code using the `Test` module or a testing framework.
- Separate tests into logical sections and provide descriptive names.
- Include both positive and negative test cases.
- Ensure tests are reproducible and independent of each other.

## Miscellaneous

- Follow the official Julia style guide unless specified otherwise.
- Use type annotations for function arguments and return types when it improves clarity.
- Use whitespace to improve code readability.
- Refactor code to improve clarity and maintainability.
- Keep lines of code concise and avoid excessive nesting.

