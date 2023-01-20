# Types and Values

JavaScript is Dynamically-typed language meaning the interpreter assigns variables a type at runtime based on the variable's value at the time.

Thus, JavaScript provide special keyword called `typeof` to get the type of the value.

```JavaScript
let foo;

console.log(typeof foo)
// undefined

console.log(typeof "hello")
// string

console.log(typeof 11)
// number

console.log(typeof true)
// boolean

console.log(typeof {})
// object

console.log(typeof [])
// object

console.log(typeof null)
// object
```

<!-- ## Primitives -->

### Strings

In JavaScript, Strings are values made up of text and can contain letters, numbers, symbols, punctuation, and even emojis!

### Numbers

Numbers are values that can be used in mathematical operations. You don’t need any special syntax for numbers — just write them straight into JavaScript.

### Booleans

In JavaScript, a boolean value is one that can either be TRUE or FALSE. If you need to know “yes” or “no” about something, then you would want to use the boolean function. It sounds extremely simple, but booleans are used all the time in JavaScript programming, and they are extremely useful. Anything that needs to be “on” or “off”, “yes” or “no”, “true” or “false”, or which just has a temporary purpose, is usually a good fit for booleans.

<!-- ## Composites -->

### [Objects]()

JavaScript objects are variables that contain multiple data values. The values within a JS object are known as properties. Objects use keys to name values, much like how is done with variables.

### [Array]()

Arrays are container-like values that can hold other values. The values inside an array are called elements.

Array elements don’t all have to be the same type of value. Elements can be any kind of JavaScript value — even other arrays.

> NOTE:
> You can also read about [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map), [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set) and [Symbol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol).s
