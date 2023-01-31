# Variable Declaration and Scope

JavaScript provide 3 ways to declare variables namely `var`, `let` and `const`. And based on the the way you declared it, it'll affect its scope and properties.

## `var`

It is an ancient way for declaring variable, and before [ES6](), the only way. But it use to cause lot of confusion because of its lexical scoping.

And that is how it different form `let` and `const`, because of its [scope]().

A general thumb rule, use `let` over `var`.

```javascript,editable
var message_with_var = "hello world";
console.log(message_with_var);
message_with_var = "new world";
console.log(message_with_var);
```

## `let` & `const`

Both `let` & `const` were introduced with [ES6](), and introduced [block scoping]() in JavaScript. And they work very similar, except for the fact that variable declared using `const` cannot change its type.

<!-- And `const` are very similar to `let` but a `const` can't be re-declared. -->

A general thumb rule, use `const` over `let` over `var`.

```javascript,editable
// let
let message_with_let = "hello world";
console.log(message_with_let);
message_with_let = "new world";
console.log(message_with_let);

// const
const message_with_const = "hello world";
console.log(message_with_const);
// message_with_const = "new world";  <-- uncomment and you'll start seeing error.
console.log(message_with_const);
```
