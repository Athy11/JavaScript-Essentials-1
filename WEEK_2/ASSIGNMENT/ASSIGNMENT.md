# ASSIGNMENT 2
**DETAILS:**

Now that you know the different operations used in JavaScript, let us try a few by incorporating them in a simple program.

Create a program where you can utilize two (2) of the primitive data types while incorporating any of the operators/operations.

## SAMPLE CODE 1
```javascript
let statement = "Is learning JS fun? ";
let isFun = true;
console.log(statement + isFun); // Adding "+" operator is called concatenation, we convert bool (isFun) to string.

OUTPUT: Is learning JS fun? true
```

## SAMPLE CODE 2
```javascript
let username = prompt("Enter your username: "); 
let isLoggedIn = prompt("Are you a member of the Programming Department(Yes/No)? ");


if (isLoggedIn.toLowerCase() == "yes" && username) {
    console.log("Welcome to CNCP, " + username + "!");
} else if (isLoggedIn.toLowerCase() !== "yes") {
    console.log("Access denied. \nPlease log in.");
} else {
    console.log("Invalid username.");
}

console.log("User logged out: " + !(isLoggedIn.toLowerCase() === "yes"));

OUTPUT:
Enter your username: Athy
Are you a member of the Programming Department (Yes/No)? YES
Welcome to CNCP, Athy!
User logged out: false
```
