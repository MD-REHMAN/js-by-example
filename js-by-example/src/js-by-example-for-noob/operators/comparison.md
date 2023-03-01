# Comparison Operators

They're used to compare 2 operands. Let's look at how they work in JavaScript.

## Inequality (`!=` & `!==`)

We have seen the **NOT(!)** operator just now. So, based on that `!=` means NOT-Equal.
But why the second operator have 2 equal sign?
Let's run the code and understand the difference.

```javascript,editable
console.log('"10" != 10 = ', "10" != 10);
console.log('"10" !== 10 = ', "10" !== 10);
```

Lets break down what's happening. So in both the cases, we are comparing `"10"` which is a _string_ with `10` which is a _number_.

In the first case, JavaScript converts the _number_ to _string_. And thus we get `false`. If you want to know why number got converted to string and not the other way around, then check [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Equality).

But in the second case, since they are not of the same type, we get `true` meaning they are not equal.

> A general thumb rule, use `!==`(strict equality) over `!=`(equality).

With this out of the way, the rest of the example will be self explanatory. Don't forget to try different value in the example.

## Equality (`==` & `===`)

Now, this operator is obvious.

> NOTE:
> The single (`=`) sign is used for [Assignment Operator]().

```javascript,editable
console.log('"10" == 10 = ', "10" == 10);
console.log('"10" === 10 = ', "10" === 10);
```

## Less than and Less than or equal (`<` & `<=`)

```javascript,editable
// Comparison Operators
console.log('5 < 5 = ', 5 < 5);
console.log('5 >= 5 = ', 5 <= 5);
```

## Greater than and Greater than or equal `>` & `>=`

```javascript,editable
console.log('5 > 5 = ', 5 > 5);
console.log('5 >= 5 = ', 5 >= 5);
```
