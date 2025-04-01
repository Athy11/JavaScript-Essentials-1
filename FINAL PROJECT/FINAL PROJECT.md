## FINAL PROJECT FOR JAVASCRIPT'S ESSENTIALS 1
### Basic ATM Simulation with PIN System
**DETAILS:** You are tasked to create a simple ATM program with basic banking transactions, simple PIN verification system, and an error handling for invalid inputs.

#### CONCEPTS TO APPLY
| Feature | Description |
| ----------- | ----------- |
| Variables | Will be used to store important data such as PIN, balance, user choices, and number of attempts. |
| Loops | Will be used to repeat the PIN verification process, limit it up to 3 tries and continuously display the ATM menu until the user chooses to exit. |
| Conditional Statements | Will be used to verify if inputs are valid, and if PIN is correct, to handle deposit and withdrawal logic, and to check for errors like insufficient funds. |
| Error Handling | Implement it using `try-catch` to catch invalid inputs, wrong menu selections, or incorrect operations such as withdrawing more than the balance. |
| User Input | Accepts dynamic input from the user using `prompt()` to enter PIN, deposit, withdraw amounts, and select menu options. |
| Type Conversion | Converts string inputs from `prompt()` into numbers using `Number()` for correct mathematical calculations. |
| Boolean Logic | Will be used to control authentication flow and determine whether the user can access the ATM or should be locked out. |

#### PROGRAM GUIDE
- The user must enter the correct PIN before accessing the ATM (default PIN = 1234).
- The ATM starts with an initial balance of ₱1000.
- Display a menu:
  - 1. Deposit
  - 2. Withdraw
  - 3. Check Balance
  - 4. Exit
- Allow the user to select options repeatedly until they choose to exit.
- Make sure that it can handle errors like:
  - Invalid PIN.
  - Wrong menu choices.
  - Non-numeric deposits or withdrawals.
  - Insufficient balance.
