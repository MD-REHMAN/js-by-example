# Identifiers

The names you assign to these variables are called Identifiers.

The general rules for constructing names for variables (unique identifiers) are:

- Names can contain letters, digits, underscores, and dollar signs.
- Names must begin with a letter, $ or \_.
- Names are case sensitive (y and Y are different variables).
- Reserved words (like `var`, `let`, `for`, `typeof` and more) cannot be used as names.

```javascript,editable
const dialogue = "How you doin!!";
// Identifier should be unique.
const dialogue = "We were on a break";
// And case sensitive
const Dialogue = "hello world";

console.log(dialogue)
console.log(Dialogue)
```

This is good time edit the example and try using `let` and `var` instead of `const`.
