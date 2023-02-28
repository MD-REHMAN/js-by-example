# Logical

## NOT (`!`)

## OR (`||`)

The **NOT**(`!`) is operating on only 1 operand, but the **OR**(`||`) needs 2 operand. That means there 4 possible scenarios. Both of them are `true`, either 1 one them is `true` and none of them are `true`.

```javascript,editable
console.log('true || true = ', true || true);
console.log('true || false = ', true || false);
console.log('false || true = ', false || true);
console.log('false || false = ', false || false);
```

So, if either of them is `true`, the output is `true`. And it's only `false` when both _(all)_ of them are `false`

## AND (`&&`)

Now, this is very similar to **OR**(`||`). Let's all the 4 possible scenarios for this as well.

```javascript,editable
console.log('true && true = ', true && true);
console.log('true && false = ', true && false);
console.log('false && true = ', false && true);
console.log('false && false = ', false && false);
```

So, it returns `true` only when both _(all)_ of them are `true`.
