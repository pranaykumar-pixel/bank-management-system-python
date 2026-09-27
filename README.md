# Python Banking Program

## Introduction

This is a simple banking program developed using Python. It is a command-line based application that allows the user to perform basic banking operations.

The user can check their balance, deposit money, withdraw money, and exit the program.

I created this project to practice basic Python programming concepts such as functions, loops, conditional statements, user input, and return values.

## Features

The program provides four main options:

1. Show Balance
2. Deposit Money
3. Withdraw Money
4. Exit

The program also validates the amount entered by the user. It does not allow zero or negative amounts for deposits and withdrawals, and it checks whether the user has enough balance before allowing a withdrawal.

## Technologies Used

* Python 3
* Python standard library
* Command Line Interface

No external libraries are required.

## Python Concepts Used

This project helped me practice:

* Functions
* Variables
* User input
* `if`, `elif`, and `else`
* `while` loop
* Function parameters
* Return values
* Arithmetic operations
* Input validation
* Menu-driven programming
* Formatted strings

## How the Program Works

When the program starts, the initial balance is set to zero.

A menu is displayed with four options.

### 1. Show Balance

The program displays the current account balance.

### 2. Deposit

The user enters the amount they want to deposit.

If the amount is greater than zero, it is added to the current balance.

If the user enters zero or a negative amount, the program displays an invalid amount message.

### 3. Withdraw

The user enters the amount they want to withdraw.

The program checks two conditions:

* The amount must be greater than zero.
* The amount must not be greater than the available balance.

If both conditions are satisfied, the amount is deducted from the balance.

### 4. Exit

The program stops running and displays a thank-you message.

## Project Structure

```text
python-banking-program/
│
├── banking_program.py
└── README.md
```

## How to Run

Make sure Python 3 is installed on your computer.

Check your Python installation using:

```bash
python --version
```

Run the program using:

```bash
python banking_program.py
```

## Example

```text
Banking Program
1. Show Balance
2. Deposit
3. Withdraw
4. Exit

Enter your choice (1-4): 2
Enter an amount to be deposited: 5000

Amount deposited successfully!
Your balance is ₹5000.00

Enter your choice (1-4): 3
Enter an amount to be withdrawn: 1000

Amount withdrawn successfully!
Your balance is ₹4000.00

Enter your choice (1-4): 1
Your balance is ₹4000.00

Enter your choice (1-4): 4

Thank you! Have a nice day!
```

## Input Validation

The program handles some common invalid inputs.

For example, if the user tries to deposit a negative amount:

```text
Enter an amount to be deposited: -500
That's not a valid amount
```

If the user tries to withdraw more money than the available balance:

```text
Enter an amount to be withdrawn: 10000
Insufficient funds
```

This prevents the balance from becoming negative.

## What I Learned

Through this project, I learned how to divide a program into different functions and connect those functions through a main program.

I also learned how to validate user input and use return values to control whether a banking operation should be completed.

## Future Improvements

This project can be extended by adding:

* Account creation
* User login and password
* Multiple bank accounts
* Transaction history
* Money transfer between accounts
* PIN verification
* Saving account information using files or a database
* Graphical user interface using Tkinter
* Web-based banking application using Flask or Django

## Author

Edakula Pranay Kumar

This project was created as a beginner Python project for learning and practicing programming concepts.

## License

This project is created for educational purposes.

