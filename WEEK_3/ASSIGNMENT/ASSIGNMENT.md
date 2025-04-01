# ASSIGNMENT 3
**DETAILS:**

Now that you've learned the control flow in JavaScript, let's test your knowledge! Program a basic ATM program that can deposit, withdraw, and check the balance using conditional statement, loops, and error handling.

## Requirements:
Your program must include:
- A loop (while, do-while, or for) to keep the program running until the user chooses to exit.
- Conditional statements (if, else if, switch) to handle different user actions.
- Error handling to prevent invalid inputs like withdrawing more money than available, or entering non-numeric values.

## Features:
- The program should start with a default balance. You can decide the default balance.
- The user should see a menu with the following options:
  1. Check Balance
  2. Deposit Money
  3. Withdraw Money
  4. Exit
- If the user selects Deposit, they must enter an amount, and it should be added to their balance.
- If the user selects Withdraw, they must enter an amount:
  - If they have enough balance, the amount is deducted.
  - If they try to withdraw more than their balance, show an error message.
- If the user selects Check Balance, display the current balance.
- The program should continue running in a loop until the user selects Exit (4).

### SAMPLE OUTPUT
```pgsql
Welcome to CNCP's ATM!  
1. Check Balance  
2. Deposit Money  
3. Withdraw Money  
4. Exit  

Enter your choice: 2  
Enter amount to deposit: 500  
Deposit successful! New balance: ₱1500  

Enter your choice: 3  
Enter amount to withdraw: 2000  
Insufficient funds! Your current balance is: ₱1500  

Enter your choice: 4  
Thank you for choosing CNCP's ATM!  
```
