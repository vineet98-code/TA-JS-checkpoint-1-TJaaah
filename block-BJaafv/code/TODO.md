1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

It has return statement, it return the value with the arrow pointing outside 
// second
function sum(a, b) {
  console.log(a + b);
}
It `doesn'/t` have any return statement. If we pass the value in paramenter, then it return the value undefined and this is main diffrence between the two 'sum'  function given above.
```
- 

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

- var first = return `a+b` = 7;
var second = undefined; = undefined;


3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?


4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?



5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

- function sayHello(name){
   return `Hello ${name}`
} 

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage(); // "Hello John"
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1  - john

showMessage(); // Output 2  - 'Hello, John'

alert(userName); // Output 3 - john
```

8. What is a Anonymous Function give example of three functions.

- An Anonymous function is a function without a function name. Only function expressions can be anonymous, function declarations must have a name.

Example - const square = function(number) { return number * number }
          const sum = function(a,b) { return a+b }
          const factorial = function (n) { return n < 2 ? 1 : n * fac(n - 1) }



9. Can function declaration be a Anonymous Function? Explain

- The function above is actually an anonymous function (a function without a name). Functions stored in variables do not need function names. They are always invoked (called) using the variable name. The function above ends with a semicolon because it is a part of an executable statement.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

- function getbook()
- function sum()
- function squared()
- function displayMessage()
- function add()
- function draw()

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
