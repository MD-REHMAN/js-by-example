# Variable Declaration and Scope

JavaScript provide 3 ways to declare variables using `var`, `let` and `const`. And based on the the way you declared it, it'll affect its scope and properties.

And to declare a variable you simple use any of 3 keyword and give a name. Just like shown below.

To understand the difference between all 3, we will take a look at 3 identical examples. Only changing the way we declare the variables.

## `var`

It is an ancient way for declaring variable, and before [ES6](), the only way. But it use to cause lot of confusion because of its functional scope (lexical scoping).

And that is how it different form `let` and `const`, because of its [scope]().

A general thumb rule, use `let` over `var`.

```javascript,editable
console.log(message);
var message = "hello world";
console.log(message);
message = "new world";
console.log(message);
```

## `let` & `const`

Both `let` & `const` were introduced with [ES6](), and introduced [block scoping]() in JavaScript. And they work very similar, except for the fact that variable declared using `const` cannot be reassigned.

### let

```javascript,editable
// console.log(message);  <-- uncomment and you'll start seeing error.
let message = "hello world";
console.log(message);
message = "new world";
console.log(message);
```

### const

```javascript,editable
// console.log(message);  <-- uncomment and you'll start seeing error.
const message = "hello world";
console.log(message);
// message = "new world";  <-- uncomment and you'll start seeing error.
console.log(message);
```

By comparing all the 3 examples you can see that `let` is more restricting than `var` and `const` and more restricting than `let`

> A general thumb rule, use `const` over `let` over `var`.

<!-- I don't wanna go in `let` vs `const` war. If you want to use `let` over `const`, your choice. 👍 -->

The name you define here are called [Identifiers](/js-by-example-for-noob/variable/identifiers.md) and there are certain rules on how to name them. Let's look at them next.
