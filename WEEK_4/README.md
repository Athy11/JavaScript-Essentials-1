## FUNCTIONS AND ARRAY
### FUNCTIONS 
Functions are reusable blocks of code designed to perform a specific task. They help organize code, avoid repetition, and make programs more modular.

#### Types:
- **Function Declaration:**
  ```javascript
  function greet(name) {
      return `Hello, ${name}!`;
  }
  ```
- **Function Expression:**
  ```javascript
  const greet = function(name) {
      return `Hello, ${name}!`;
  };
  ```
- **Arrow Functions:**
  ```javascript
  const greet = (name) => `Hello, ${name}!`;
  ```

#### Key Features:
- Functions can have default parameters:
  ```javascript
  function greet(name = "Guest") {
      return `Hello, ${name}!`;
  }
  ```
- Functions can return other functions or be passed as arguments.
- Arrow functions have implicit `return` for single-line expressions and no `this` binding.

Reference: [Function Basics](https://javascript.info/function-basics) | [Function Expressions](https://javascript.info/function-expressions) | [Arrow Functions](https://javascript.info/arrow-functions-basics)

### ARRAY 
Arrays are ordered collections of data that can store multiple values of any type, allowing efficient storage and manipulation of lists. In JavaScript, arrays are technically objects, but they have special methods and behaviors tailored for handling sequences of values.
#### Syntax:
```javascript
let fruits = ["Apple", "Banana", "Cherry"];
```

#### Common Operations:
- **Access Elements:**
  ```javascript
  console.log(fruits[0]); // "Apple"
  ```
- **Add/Remove Elements:**
  ```javascript
  fruits.push("Date");  // Add to end
  fruits.pop();          // Remove from end
  fruits.shift();        // Remove from start
  fruits.unshift("Fig"); // Add to start
  ```
- **Iterate Over Elements:**
  ```javascript
  for (let fruit of fruits) {
      console.log(fruit);
  }
  ```

#### Key Points:
- Arrays have a `length` property.
- Methods like `map`, `filter`, and `reduce` enable functional programming.

Reference: [Arrays](https://javascript.info/array)

### LET’S PRACTICE YOUR KNOWLEDGE!
Now that you've learned how array and functions work and its syntax, let's put it to test! 
Enhance your previous work by implementing array and/or functions.
