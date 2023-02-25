# Operators

Operators are symbols that are used to perform operations on operands like addition, subtraction, multiplication, and more. JavaScript has dozens of operators, so let’s focus on the ones you’re likely to see most often.

## Assignment

Operators like `=`.

We have already seen this operator in [variable]() section, and this operator assigns values.

```javascript,editable
// Here we assigned the value `hello` to the variable named `message`.
let message = "hello"
console.log(message)
```

There are also different types of assignments operators like `&&=`, `||=`, `+=`, `-=`, `*=`, `/=`, `%=`, `??=` and more. But we learn about them later.

## [Arithmetic]()

Operators like `+`, `-`, `*`, `/` and `%`.

```javascript,editable
// Division
console.log(11/3)
// Multiplication
console.log(5*2)
// Subtraction
console.log(101-1)
// Addition
console.log(10+1)
// Addition can also be use to concatenate (combine) strings
console.log("Hello " + "World ")
// Modulus (Remainder)
console.log(10%3)

// Combination
console.log(1/2*3-4+5)
console.log(5-4+3*1/2)
```

Arithmetic operators follows the [BODMAS rule](https://www.google.com/search?q=what+is+BODMAS), thus the order in which you write them is ir-relevant. You can use small brackets `()` to priorities certain operation.

<!-- This will be moved to advanced topic -->
### Increment & Decrement

```javascript,editable
let count = 1;
console.log("Init count value: ", count);

// Increment
// `++count` is equal to `count = count + 1`
console.log("count value after increment: ", ++count);

// Decrement
// `--count` is equal to `count = count - 1`
console.log("count value after decrement: ", --count);

console.log("Final count value: ", count);
```

Increment & Decrement operator can also be used after the operand (like `count++`). The difference it will return the value before it is incremented.

## Bitwise Operators

Operators like `^`, `~`, `<<`, `>>`, `>>>`, `|` and `&`

These are not as commonly used, so we'll look at them later.

## [Comparison & Logical Operators](/js-by-example-for-noob/operators/comparison-and-logical.md)

These are the coolest and one of the most frequently used one (unlike Bit-wise operators) as well. So we will dive deep and understand each of them one-by-one.

Let see how they look.
Operators like `==` , `===`, `!=` , `!==`, `>`, `<`, `>=`, `<=`,`!`, `||` and `&&`.

```javascript,editable

// Comparison Operators 
const random = Math.random().toFixed(1);

console.log('\n"10" == 10 = ', "10" == 10);
console.log('"10" === 10 = ', "10" === 10);
console.log('"10" != 10 = ', "10" != 10);
console.log('"10" !== 10 = ', "10" !== 10);

console.log('\nrandom = ', random);
console.log('\nrandom > 0.5 = ', random > 0.5);
console.log('random >= 0.5 = ', random >= 0.5);
console.log('random < 0.5 = ', random < 0.5);
console.log('random >= 0.5 = ', random >= 0.5);

// Logical Operators
console.log('!true = ', !true);
console.log('!false = ', !false);

console.log('\ntrue || true = ', true || true);
console.log('true || false = ', true || false);
console.log('false || true = ', false || true);
console.log('false || false = ', false || false);

console.log('\ntrue && true = ', true && true);
console.log('true && false = ', true && false);
console.log('false && true = ', false && true);
console.log('false && false = ', false && false);
```

Don't they look complicated. Let's look at them one by one.

<!-- [I will move it to advance topic, And give it a better name] -->

## Extra Cool Stuff

### The Nullish Coalescing Operator

The ?? operator returns the first argument if it is not nullish (null or undefined).

Otherwise it returns the second argument.

```javascript,editable
let name = null;
let text = "missing";
let result = name ?? text;
```

### The Optional Chaining Operator (?.)

The ?. operator returns undefined if an object is undefined or null (instead of throwing an error).

```javascript,editable
const naruto = {
  clan:"Uzumaki",
  village: "Leaf",
  chakra_nature:["wind"],
};
const sasuke = null;
console.log(naruto?.clan)
console.log(sasuke?.clan)  // <-- Try removing the `?`
```
