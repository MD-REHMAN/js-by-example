# Lexical Scope vs Block Scope

I have to describe it later

A big example to show both the scope.

```javascript,editable
var global_var = 0;
let global_let = 0;
const global_const = 0;


// An IFEE, more on this later
(() => {
  var local_var = 1;
  let local_let = 1;
  const local_const = 1;
  if(true) {
    var block_var = 2;
    let block_let = 2;
    const block_const = 2;

    // Every vaiables will be available here because of closure (more on that later) and scope.
  }

  // Global variable will be available even here, because of the property called closure (more on that later).
  console.log(global_var); // 0
  console.log(global_let); // 0
  console.log(global_const); // 0

  // Local variable will be availble in local scope.
  console.log(local_var); // 1
  console.log(local_let); // 1
  console.log(local_const); // 1

  // Block let and const have block scope, thus they will throw error.
  console.log(block_var); // 2
  console.log(block_let); // error
  console.log(block_const); // error
})();


// Global variables are available
console.log(global_var); // 0
console.log(global_let); // 0
console.log(global_const); // 0

// Local variable will not be availble outside the local scope.
console.log(local_var); // error
console.log(local_let); // error
console.log(local_const); // error

// Even the var will not be availble outside the lexical scope.
console.log(block_var); // error
console.log(block_let); // error
console.log(block_const); // error

```

Let's look at them independently. And break them down

```javascript,editable

```
