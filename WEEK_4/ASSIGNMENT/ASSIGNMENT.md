# ASSIGNMENT 4
**DETAILS:**

Now that you've learned the control flow in JavaScript, let's test your knowledge! Program a basic ATM program that can deposit, withdraw, and check the balance using conditional statement, loops, and error handling.

## Requirements:
Your program must include:
- A loop (while, do-while, or for) to keep the program running until the user chooses to exit.
- Conditional statements (if, else if, switch) to handle different user actions.
- Error handling to prevent invalid inputs like withdrawing more money than the balance, or entering non-numeric values.
- An array to store and display the transaction history.

## Features:
- The program should start with a default balance. You can decide the default balance.
- The user should see a menu with the following options:
  1. Check Balance
  2. Deposit Money
  3. Withdraw Money
  4. View Transaction History
  5. Exit
- If the user selects Deposit, they must enter an amount, and it should be added to their balance.
- If the user selects Withdraw, they must enter an amount:
  - If they have enough balance, the amount is deducted.
  - If they try to withdraw more than their balance, show an error message.
- If the user selects Check Balance, display the current balance.
- If the user selects View Transaction History, the system should display all recorded transactions.
- The program should continue running in a loop until the user selects Exit (5).

### SAMPLE OUTPUT
```pgsql
Welcome to CNCP ATM!  
1. Check Balance  
2. Deposit Money  
3. Withdraw Money  
4. View Transaction History  
5. Exit  

Enter your choice: 2  
Enter amount to deposit: 500  
Deposit successful!
New balance: ₱1500  

Enter your choice: 3  
Enter amount to withdraw: 200  
Withdrawal successful!
New balance: ₱1300  

Enter your choice: 4  
Transaction History:  
Deposited: ₱500  
Withdrew: ₱200  

Enter your choice: 5  
Thank you for using the CNCP ATM!    
```
