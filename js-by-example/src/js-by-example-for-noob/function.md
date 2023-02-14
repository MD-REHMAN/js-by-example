# Function

Functions are one of the fundamental building blocks in JavaScript.

And the purpose of Function is to execute a set of instruction when called.

Let's look at one.

```javascript,editable
function add(a, b) {
  return a + b;
}
const result = add(2, 5);
console.log(result);
```

Now there are few things to understand here, lets get it one by one.

- `function`: This is the keyword (reserved word) used to define.
- `add`: This is name of the function, it can be anything as long as they are valid [identifier]().
- `(a, b)`: These can further be divided in 2 types
  - `a, b`: These are called **parameters**, here we have 2 of them separated by a **,**. These are also know as **inputs**
  - `()`: All the **parameters** are wrapper by them.
- `{}`: These represent the body of the function. when the function is called, code withing these brackets will get executed.
- `return`: This is the keyword (reserved word) used to return data from the function. These are also known as **outputs**.
- `add(2, 5)`: Lets break it down.
  - `add`: The name of the function which me want to call.
  - `2, 5`: These are called **arguments**, and this denotes that `a=2` and `b=5`.
  - `()`: All the **arguments** are wrapper by them.

Try removing the return keyword, and run the example.

---

In Javascript, functions can also be assigned to a variable. Lets check that out in code.

```javascript,editable
function add(a, b) {
  return a + b;
}
const alsoAdd = add;
const result = alsoAdd(2, 5);
console.log(result);
```

There are two things to note in the above code.

- Just like any other value, functions can also be assigned to a variable. And you call them using this variable name, as well as the old name
- Remember just like objects, by assigning functions to a variable we are not copying it, instead just passing its reference.
