## CONTROL FLOW

### CONDITIONAL STATEMENTS
Conditional statements are used to perform different actions based on whether a specified condition is true or false. They help control the flow of a program by making decisions.
- `if` — executes a block of code if a condition is true.
  ```javascript
  let age = 18;
  if (age >= 18) {
    console.log("You are an adult.");
  
  OUTPUT: You are an adult.
  ```

- `if-else` — executes one block if the condition is true and another block if it is false.
  ```javascript
  let temp = 25;
  if (temp > 30) {
    console.log("It's hot outside!");
  } else {
    console.log("The weather is nice.");
  }
  
  OUTPUT: The weather is nice.
  ```

- `else if` — tests another condition if the first one is false.
  ```javascript
  let score = 85;
  if (score >= 90) {
    console.log("Grade: A");
  } else if (score >= 80) {
    console.log("Grade: B");
  } else if (score >= 70) {
    console.log("Grade: C");
  } else {
    console.log("Grade: F");
  }
  
  OUTPUT: Grade B
  ```

- `switch` — selects one of many blocks of code to execute.
  ```javascript
  let day = "Monday";

  switch (day) {
    case "Monday":
        console.log("Start of the weekday.");
        break;
    case "Friday":
        console.log("Weekend is coming!");
        break;
    default:
        console.log("Another regular day.");
  }
  
  OUTPUT: Start of the weekday.
  ```

### LOOPS
Loops are used to execute a block of code repeatedly as long as a specified condition is true. Once the condition becomes false, the loop stops.
- `for` loop — Returns multiple times until the number of iterations returns false.
  ```javascript
  for (let i = 1; i <= 5; i++) {
    console.log("Count:", i);
  
  OUTPUT:
  Count: 1
  Count: 2
  Count: 3
  Count: 4
  Count: 5
  ```

- `while` loop — Executes a block of code as long as the condition is true.
  ```javascript
  let count = 1;
  while (count <= 5) {
    console.log("Count:", count);
    count++;
  }
  
  OUTPUT:
  Count: 1
  Count: 2
  Count: 3
  Count: 4
  Count: 5

  ```

- `do-while` loop — Executes the block of code once before checking the condition.
  ```javascript
  let num = 1;
  do {
    console.log("Number:", num);
    num++;
  } while (num <= 5);
  
  OUTPUT:
  Count: 1
  Count: 2
  Count: 3
  Count: 4
  Count: 5
  ```
  
### ERROR HANDLING
Error handling prevents runtime errors from crashing the program.

#### TRY-CATCH-FINALLY
Catches errors that occur in the try block and the finally block runs regardless of whether an error occurs or not.
 ```javascript
function readFile(filename) {
    try {
        if (filename !== "data.txt") {
            throw new Error("File not found");
        }
        console.log("File read successfully.");
    } catch (error) {
        console.log("Error reading file:", error.message);
    } finally {
        console.log("File read attempt completed.");
    }
}

readFile("data.txt");  
readFile("missing.txt");  

OUTPUT:
File read successfully.
File read attempt completed.
Error reading file: File not found
File read attempt completed.
```

#### THROW STATEMENT
Manually throws an error prompt.
 ```javascript
function getRole(role) {
    if (role !== "admin" && role !== "user") {
        throw "Invalid role!";
    }
    return `Access granted for ${role}.`;
}

try {
    console.log(getRole("admin")); // This will be granted access as it's the assigned value in getRole function
    console.log(getRole("guest")); // This will throw an error
} catch (error) {
    console.log("Caught an error:", error);
}

OUTPUT:
Access granted for admin.
Caught an error: Invalid role!
```

### LET’S PRACTICE YOUR KNOWLEDGE!




