CSS Variables

## Review

In this lesson, we learned how to use CSS variables to make property values more legible and easily replaced. We also learned about the power of scoping, overriding variables, and fallback values. Finally, we practiced using variables with media queries to create a website with dynamic web themes.

- Variables mitigate the need to repeat property values and make CSS code easier to read.
- You can use variables in CSS to store values.
- Variable declaration must start with a double hyphen (`--`).
- Variables must be used as values for CSS properties.
- Variables must be used as an argument inside of the `var()` function.
- Variables are subject to both scope and inheritance.
- Globally scoped variables are defined inside the `:root` pseudo-class.
- Overriding a variable is done by redefining that variable’s value inside of the desired selector ruleset.
- Fallback values can be used to provide a backup value if the initial variable is invalid.
- Multiple fallback values can be provided by adding more values inside cascading `var()` functions.
- Responsively designed web pages can be created by combining variables with media queries.
