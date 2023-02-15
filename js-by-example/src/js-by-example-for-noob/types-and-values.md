# Types and Values

JavaScript is Dynamically-typed language meaning the interpreter assigns variables a type at runtime based on the variable's value at the time.

<!-- version 2 -->
<!-- JavaScript is Dynamically-typed language meaning variables in JavaScript are not directly associated with any particular value type, and any variable can be assigned (and re-assigned) values of all types: -->

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

## Primitives

Every programing language support different type of values, for different purpose. The most fundamental of them are called [Primitives](#primitives).
<br/>
<br/>
Let's look at the most popular one.

### Strings

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

console.log(typeof new Date())
// string

```

### Numbers

Numbers are values that can be used in mathematical operations. You don’t need any special syntax for numbers — just write them straight into JavaScript.

```javascript,editable
console.log(7)
// number
console.log(3.14159265359)
// number

// But what's the limit, well you can check like this
console.log(Number.MAX_SAFE_INTEGER)
// 9007199254740991
console.log(Number.MIN_SAFE_INTEGER)
// -9007199254740991
```

> NOTE:
> More on `Number` later. But if you're curious, then read the [source](https://developer.mozilla.org/en-US/docs/Glossary/Primitive).

### Booleans

They are rather simple, they can only be `true` and `false`.

```javascript,editable
console.log(typeof true)
// boolean

console.log(typeof false)
// boolean

```

### Undefined & Null

`undefined` is default value for every variable till, it is defined. And `undefined` indicates the absence of a value.

While `null` indicates the absence of an object

## [Objects]()

Objects are variables that contain multiple data values. The values within a JS object are known as properties. Objects use keys to name values, much like how is done with variables.

Objects are nothing but collection of values.

Discuss it later.

<!-- Objects are **Reference values**. -->

```javascript,editable
// Well Arrays are also objects
console.log(typeof [])
// object

// And so is null
console.log(typeof null)
// object
```

## [Array]()

Array are special type of object. That hold other values in order.

The values inside an array are called elements.

Array elements don’t all have to be the same type of value. Elements can be any kind of JavaScript value — even other arrays or objects.

<!-- Array are **Reference values**. -->

```javascript,editable
console.log(typeof [1,2,3,4,5])
// object

console.log(typeof ["Naruto", "Sasuke", "Kakashi"])
// object

console.log(typeof ["Naruto", 1, true, {}, null, undefined])
// object
```

> NOTE:
> You can also read about [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map), [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set), [BigInt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#bigint_type) and [Symbol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol). But we don't have to worry about them right now.
