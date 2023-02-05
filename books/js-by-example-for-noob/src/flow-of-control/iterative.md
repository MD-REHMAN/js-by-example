# Loops

## For

```javascript,editable
for(let i=0; i<7; i++) {
  console.log("i = ", i)
}
```

## While

The `while` keyword can be used to run a loop while a condition is `true`.

```javascript,editable
let i=0;
while(i<7) {
  console.log("i = ", i)
  i++;
}
```

## Do while

The `do` keyword is used to start the body of the loop and `while` keyword is used at the end to declare the condition.

```javascript,editable
let i=0;
do {
  console.log("i = ", i)
  i++;
}while(i<7);
```

As you can see the condition is checked at the end, the content of the loop will always execute at-least once.
