# Operators

Operators are the symbols between values that allow different operations like addition, subtraction, multiplication, and more. JavaScript has dozens of operators, so let’s focus on the ones you’re likely to see most often.

## Assignment

Operators like `=`.

We have already seen this operator in [variable]() section, and this operator assigns values.

```javascript,editable
// Here we assigned the value `hello` to the variable named `message`.
let message = "hello"
console.log(message)
```

## [Arithmetic](/operators/arithmetic.md)

Operators like `+`, `-`, `*` and `/`.

```javascript,editable
// Simple example to show all Arithmetic operators
let simple_math = 1/1*1-1+1;
console.log(simple_math)
```

> **NOTE:**
> Arithmetic operators follows the [BODMAS rule](https://www.google.com/search?q=what+is+BODMAS), thus the order in which you write them is ir-relevant.

## [Logical Operators](/operators/logical.md)

Operators like `==` , `===`, `!=` , `!==`, `>`, `<`, `>=`, and `<=`

```javascript,editable

```

## [Conditional Operators](/operators/conditional.md)

Operators like `||` , `!` and `&&`

```javascript,editable

```

## [Bitwise Operators](/operators/bitwise.md)

Operators like `|` , `!` and `&`

```javascript,editable

```

## The Nullish Coalescing Operator

The ?? operator returns the first argument if it is not nullish (null or undefined).

Otherwise it returns the second argument.

```javascript,editable
let name = null;
let text = "missing";
let result = name ?? text;
```

## The Optional Chaining Operator (?.)

The ?. operator returns undefined if an object is undefined or null (instead of throwing an error).

```javascript,editable
const ninja = {name:"Naruto", chakra_nature:["wind"], clan:"Uzumaki", village: "Leaf"};
console.log(ninja?.name)
console.log(ninja?.weakness)
```
