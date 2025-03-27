## FUNDAMENTALS OF JAVASCRIPT

### VARIABLES
- `let` → Used for variables that can change.
- `const` → Used for values that should not change.
- `var` → Older way of declaring variables (try to avoid using it).

```javascript
let name = "John";
const age = 30;
var country = "USA";
```

### DATA TYPES
In JavaScript there are eight data types and it is categorized into primitive and non-primitive types.
**PRIMITIVE DATA TYPE** - Primitive types are immutable and stored directly in memory.
| Data Type | Description | Example |
| ----------- | ----------- | ----------- |
| Number | Represents both integers and floating-point numbers. | let num = 42; |
| BigInt | Used for very large integers. | let big = 1234567890123; |
| String | An array of characters. | let str = "Hello"; |
| Boolean | Represents true or false values. | let isTrue = false; |
| Undefined | A declared variable without an assigned value. | let x; |
| Null | Represents an intentional absence of value. | let y = null; |
| Symbol | A unique identifier, often used for object properties. | let sym = Symbol("id"); |

**NON-PRIMITIVE DATA TYPE** - This stores references to objects in memory.
| Data Type | Description | Example |
| ----------- | ----------- | ----------- |
| Object | A collection of key-value pairs, including arrays and function. | let obj = { name: "Alice Gow" }; |


### ARITHMETHIC OPERATORS
These operators perform mathematical operations on numbers. Used for mathematical calculations or scientific calculations.

| Operator | Description |
| ----------- | ----------- |
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| / | Division |
| % | Modulus (Remainder) |
| ** | Exponentiation (Power) |
| ++ | Increment (adds 1) |
| -- | Decrement (subtracts 1) |

### COMPARISON OPERATORS
These operations compare two values and return a Boolean value (true or false).
| Operator | Description |
| ----------- | ----------- |
| == | Equal to |
| === | Strict Equal (checks value and type) |
| != | Not Equal |
| !== | Strict Not Equal |
| > | Greater than |
| < | Less than |
| >= | Greater than or equal to |
| <= | Less than or equal to |

### LOGICAL OPERATORS
Logical operators also use Boolean values and help in decision-making by combining the conditions.

`&&` - AND OPERATOR (true if both conditions are true)

`||` - OR OPERATOR (true if at least one condition is true)

`!` - NOT OPERATOR (inverts a Boolean value)

### INPUT/OUTPUT OPERATIONS
These operations handle interactions between the program and the user, such as displaying messages or taking input from the user.
| Operator | Description |
| ----------- | ----------- |
| Output to Console | console.log()|
| Output with Formatting |console.table()|
| Error Logging|console.error()
|Warning Message|console.warn()|
|Prompt for Input|prompt()|
|Confirm Dialog|confirm()|
|Alert Message|alert()|

## LET’S PRACTICE YOUR KNOWLEDGE!
Now that you know the different operations used in JavaScript, let us try a few by incorporating them in a simple program.

Create a program where you can utilize two (2) of the primitive data types while incorporating any of the operators/operations.



