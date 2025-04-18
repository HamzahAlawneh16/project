#  Java Banking System

A simple **Banking System built with Java and Swing GUI**, allowing users to perform basic banking operations through an intuitive graphical interface.

---

##  Project Description

This project simulates a basic banking system where users can:

- Create a new bank account
- View all existing accounts
- Deposit money into an account
- Withdraw money from an account

Each account is represented as an object of the `BankAccount` class. The system manages all accounts using an `ArrayList` in the `Bank` class, which allows adding, searching, and updating account details. The graphical interface is built using Java's **Swing** library, allowing for real-time interaction between users and the system.

This project is designed to help beginners understand the implementation of **Object-Oriented Programming (OOP)** concepts such as classes, objects, inheritance (if needed), and encapsulation. It also introduces GUI development in Java through event-driven programming.

---

##  University Project

This project was created as part of a university course assignment in Java programming. It was developed collaboratively by:

- **Hamzeh Alalwani**
- **Yousef Abu Khadra**
- **Moamen Beshtawi**

The project reflects our understanding of core Java concepts and our ability to work as a team to develop a functional and user-friendly desktop application.

---

## ⚙ Features

- ✅ Create new accounts with a name, unique account number, and starting balance  
- ✅ View all registered accounts in a structured format  
- ✅ Deposit money into a specific account using account number  
- ✅ Withdraw money with validation to prevent overdrawing  
- ✅ Responsive and user-friendly GUI built with Swing  

---

##  Project Structure

- `BankAccount.java`: Represents a single bank account with attributes like name, account number, and balance. Contains methods for deposit and withdrawal.
- `Bank.java`: Manages the list of `BankAccount` objects. Provides methods to add accounts, find accounts, and perform transactions.
- `BankGUI.java`: The graphical interface class that connects user actions to backend logic using Swing components.

---

##  GUI Overview

The application interface includes:

- Input fields for account name, number, and amount
- Buttons to perform actions:
  - **Create Account**
  - **View Accounts**
  - **Deposit**
  - **Withdraw**
- A display area (JTextArea) that shows messages and account information
- User-friendly feedback on successful or failed operations


##  Authors

Developed by **Hamzeh Alawneh**, in collaboration with **Yousef Abu Khadra** and **Moamen Beshtawi** as part of a university project.

If you like this project, feel free to  star it!

---

##  Future Improvements

- Add login functionality for users  
- Store data in files or a database  
- Add transaction history per account  
- Improve error handling and input validation
---
