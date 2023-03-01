# Logical

Now we know the NOT (`!`) Operator and all the [Comparison Operators](). These two operators are just logical (pun intended).

## OR (`||`)

<!-- The **NOT**(`!`) is operating on only 1 operand, but the **OR**(`||`) needs 2 operand. That means there 4 possible scenarios. Both of them are `true`, either 1 one them is `true` and none of them are `true`. -->

```javascript,editable
const num = 7;
console.log(num < 5 || num > 10);
```

So, if either of them is `true`, the output is `true`. And it's only `false` when both _(all)_ of them are `false`.

```javascript,editable
console.log('true || true = ', true || true);
console.log('true || false = ', true || false);
console.log('false || true = ', false || true);
console.log('false || false = ', false || false);
```

This is called truth table. Which shows how the OR operator with respond all 4 possible case.

## AND (`&&`)

Now, this is very similar to **OR**(`||`).

```javascript,editable
const num = 7;
console.log(num > 5 && num < 10 && num < 15);
```

So, it returns `true` only when both _(all)_ of them are `true`.

> Don't forget to play with example. What will happen if you replace `7` with `11`.

Let's all the 4 possible scenarios for this as well. Assuming we have 2 operands.

```javascript,editable
console.log('true && true = ', true && true);
console.log('true && false = ', true && false);
console.log('false && true = ', false && true);
console.log('false && false = ', false && false);
```
