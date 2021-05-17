1. Using loops take 10 inputs from user and find the average of all the numbers.

function averageCalcultor () {
let result = 0;
for (let i = 0; i <=10; i++) {
  let count = Number(prompt("Enter number"));
   result = result + count;
}
return(result / 10);
}




2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```

function println(str) {
  console.log(str);
}


3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

- function getEvenSum(max){
   if(max % 2 == 0){
     return 
   }
}
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.



6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // output - "Bigger than 5" - num is greater than 5
check(1); // output  - "Smaller than 5" - num is less than 5
check(5); // output  - 5  - return the same number
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // "You are arya" - name is assigning to the Arya and then returning the return value 
getOutput('John'); // "You are john" - name is assigning to the John and returning the return value
getOutput(); // "Who are you" - returning the same name

```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // You are arya - name is assigning to the Arya and then returning the return value 
getOutput('John'); // You are john - name is assigning to the John and returning the return value
getOutput(); //    Who are you - returning the same name
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

- For loop - The for statement creates a loop that consists of three optional expressions, enclosed in parentheses and separated by semicolons, followed by a statement (usually a block statement to be excuted in the loop.
syntax - 

for ([initialization]; [condition]; [final-expression])
   statement 

for(let i = 0; i < 9; i++){
  console.log(i);
}

- The following for statement starts by declaring the variable i and initializing it to 0. It checks that i is less than han nine, performs the two succeeding statements, and increments i by 1 after each pass through the loop.



while loop- The while statement creates a loop that excutes a specified statement as long as the test condition evaluates to true. The condition is evaluated before executing the statement.
 
 syntax - while (condition)
    statement 

    var n = 0;
    var x = 0;

    while (n < 3) {
      n++;
      x += n;
    }

Each iteration, the loop increments n and adds it to x. Therefore, x and n take on the following values:
  - After the first pass: n = 1 and x = 1 
  - After the second pass: n = 2 and x = 3
  - After the third pass: n = 3 and x = 6

After completing the third pass, the condition n < 3 is no longer true, so the loop terminates.