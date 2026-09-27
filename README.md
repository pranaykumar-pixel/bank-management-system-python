# Python Bank Management System

## Introduction

This is a simple Bank Management System developed using Python. The project is a menu-driven program that allows a user to perform basic banking operations through the command line.

The user can check their current balance, deposit money, withdraw money, or exit the program.

This project was created as a beginner Python project to practice functions, loops, conditional statements, user input, and basic program logic.

## Features

The program provides the following options:

1. Show Balance
2. Deposit Money
3. Withdraw Money
4. Exit

The program also checks whether the entered amount is valid and displays a message when there are insufficient funds.

## Technologies Used

* Python 3
* Git
* GitHub

## Python Concepts Used

The project uses several basic Python concepts:

* Functions
* Variables
* User input
* Conditional statements
* While loop
* Return statements
* Function parameters
* Arithmetic operations
* Input validation
* Menu-driven programming

## How the Program Works

When the program starts, the initial balance is set to zero.

The program then displays a menu with four options.

### Show Balance

The user can select this option to view their current account balance.

### Deposit

The user enters the amount they want to deposit. If the amount is valid, it is added to the current balance.

### Withdraw

The user enters the amount they want to withdraw. The program checks whether the account has enough money before completing the withdrawal.

If the withdrawal amount is greater than the available balance, the program displays an insufficient funds message.

### Exit

The user can select the exit option to stop the program.

## Project Structure

```text
python-bank-management-system/
│
├── bank_management_system.py
└── README.md
```

## How to Run

Make sure Python 3 is installed on your computer.

Check the Python version:

```bash
python --version
```

Run the program:

```bash
python bank_management_system.py
```

## Example Output

```text
Banking Program

1. Show Balance
2. Deposit
3. Withdraw
4. Exit

Enter your choice (1-4): 1

Your balance is ₹0.00

Enter your choice (1-4): 2

Enter an amount to be deposited: 5000

Enter your choice (1-4): 1

Your balance is ₹5000.00

Enter your choice (1-4): 3

Enter an amount to be withdrawn: 1000

Enter your choice (1-4): 1

Your balance is ₹4000.00

Enter your choice (1-4): 4

Thank you! Have a nice day!
```

## Learning Outcome

By creating this project, I practiced how to divide a Python program into functions and how to use a menu-driven approach.

I also learned how to take input from users, perform calculations, validate input, and control the flow of a program using loops and conditional statements.

## Future Improvements

This project can be extended with more advanced banking features, such as:

* Account creation
* User login and password
* Multiple bank accounts
* Transaction history
* Transfer money between accounts
* PIN verification
* Saving account information using files or a database
* A graphical user interface
* A web-based banking application

## Author

Edakula Pranay Kumar

This project was developed as a beginner Python project for learning and practicing programming concepts.

## License

This project is created for educational purposes.
