# Types and Values

JavaScript is Dynamically-typed language meaning the interpreter assigns variables a type at runtime based on the variable's value at the time.

Thus, JavaScript provide special keyword called `typeof` to get the type of the value.

```javascript,editable
console.log(typeof undefined)
// undefined

console.log(typeof "hello")
// string

console.log(typeof 11)
// number

console.log(typeof true)
// boolean

console.log(typeof {})
// object
```

<!-- ## Primitives -->

## Strings

In JavaScript, Strings are values made up of text and can contain letters, numbers, symbols, punctuation, and even emojis!

Let's look at different type of strings.

```javascript,editable
console.log(typeof "hello!!")
// string

console.log(typeof "7")
// string

console.log(typeof "")
// string

console.log(typeof " ")
// string

```

## Numbers

Numbers are values that can be used in mathematical operations. You don’t need any special syntax for numbers — just write them straight into JavaScript.

```javascript,editable
console.log(7)
// number

// But what's the limit, well you can check like this
console.log(Number.MAX_SAFE_INTEGER)
// 9007199254740991
console.log(Number.MIN_SAFE_INTEGER)
// -9007199254740991
```

> NOTE:
> More on `Number` later.

## Booleans

They are rather simple, they can only be `true` and `false`.

```javascript,editable

console.log(typeof true)
// boolean

console.log(typeof false)
// boolean

```

## [Objects]()

JavaScript objects are variables that contain multiple data values. The values within a JS object are known as properties. Objects use keys to name values, much like how is done with variables.

```javascript,editable
// Well Arrays are also objects
console.log(typeof [])
// object

// And so is null
console.log(typeof null)
// object
```

## [Array]()

Arrays are container-like values that can hold other values. The values inside an array are called elements.

Array elements don’t all have to be the same type of value. Elements can be any kind of JavaScript value — even other arrays.

```javascript,editable
console.log(typeof [1,2,3,4,5])
// object

console.log(typeof ["Naruto", "Sasuke", "Kakashi"])
// object
```

> NOTE:
> You can also read about [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map), [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set) and [Symbol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol).
