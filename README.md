![A](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTV5E2k4ZwECgHkeSUtW96YOpRTAYYmQIQpdA&s) 


# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
```

1. **const**: const should be used whenever a function expression is assigned to a variable.
2. **The function name**: The name you choose for the function.
3. **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
   The arrow syntax: Indicates that this will be a function.
4. **The body**: The statements that make up the function itself. Surrounded by curly braces.

**_Example:_**

```javascript
const greet = (name) => {
  console.log('Hello, ' + name + '!')
}
```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ).

## 2. Calling a function

To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

**_Example:_**

`greet('Alice');` // Outputs: Hello, Alice!

## 3. Return values

Functions can process data input and output a value using the _return_ keyword.

**_Example:_**

```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4)

console.log(total) // Expected value: 6
```
For more information on functions and how they are used in JS, check out the MDN docs.
[MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

