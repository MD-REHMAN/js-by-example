# Hoisting

Hoisting in JavaScript is a behavior in which a function or a variable can be used before declaration

```javascript,editable
// using test before declaring
console.log(test);   // undefined
var test;
```

### Variable Hoisting

In terms of variables and constants, keyword var is hoisted and let and const does not allow hoisting.

### Function Hoisting

A function can be called before declaring it. For example,

// program to print the text
greet();

```javascript,editable
function greet() {
    console.log('Hi, there.');
}
```
