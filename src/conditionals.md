# Conditionals

An integral part of any programming language are ways to modify control flow: if/else, for, and others. Let's talk about them in JavaScript.

### Ternary

**Syntax**
</br>

```javascript
condition ? exprIfTrue : exprIfFalse;
```

```javascript,editable
const true_value = true ? "I am True" : "I am False";
const false_value = false ? "I am True" : "I am False";

console.log("true_value = ", true_value);
console.log("false_value = ", false_value);

```

### If/else

Branching with if-else is similar to other languages.

```javascript,editable
if (7 % 2 === 0) {
  console.log('7 is even')
} else {
  console.log('7 is odd')
}

// You can have if without else
if (8 % 4 === 0) {
  console.log('8 is divisible by 4')
}

// Many branches
const duck = 'blue';
if (duck === 'yellow') {
  console.log('Rubber ducky')
} else if (duck === 'brown') {
  console.log('Live duck')
} else {
  console.log('Ive never seen a blue duck before.')
}
```

### Switch

Switch statements are conditionals that may have many branches (like if / else if).

```javascript,editable
// a simple switch statment
const fruit = 'banana'
switch (fruit) {
  case 'blueberry':
    console.log('blue')
    // everything after the true case executes
    // use 'break' if you aren't returning a value
    break;
  case 'banana':
    console.log('yellow')
    break;
    // multiple cases can resolve to the same branch
  case 'apple':
  case 'raspberry':
    console.log('red')
    break;
  default:
    console.log('not blue, yellow or red')
}
```
