# Banking System Using Java

A comprehensive collection of Java implementations demonstrating various banking system functionalities using different programming approaches and techniques.

## Overview

This project contains **5 different implementations** of a banking system in Java, each showcasing different programming concepts and design patterns. These implementations are ideal for learning Java fundamentals and object-oriented programming principles.

## Implementations

### 1. Array-Based Banking System
**Features:**
- Account management using arrays
- Maximum 20 accounts support
- Minimum balance requirement: ₹500
- Auto-generated account numbers
- CRUD operations (Create, Read, Update, Delete)

**Operations:**
- Create new account
- Display account details
- Deposit money
- Withdraw money
- Delete account

### 2. Interface-Based Banking System
**Features:**
- Demonstrates polymorphism through interfaces
- Multiple bank implementations (HDFC & State Bank)
- Different balance tracking mechanisms
- Clean separation of concerns

**Key Components:**
- `IAccount` interface
- `HDFCAccount` implementation
- `StateBankAccount` implementation

### 3. Scanner Class Implementation
**Features:**
- User-friendly input using Scanner class
- Basic banking operations
- Input validation for insufficient funds
- Simple and easy to understand

**Operations:**
- Get account details
- Deposit funds
- Withdraw funds with balance check

### 4. Constructor-Based Banking System
**Features:**
- Object initialization using constructors
- Uses DataInputStream for input
- Maintains minimum balance of ₹500
- Interactive menu-driven program

**Account Details:**
- Name
- Account type
- Balance
- Deposit/Withdrawal history

### 5. Flag-Based Banking System with Array
**Features:**
- Array of objects for multiple accounts
- Flag mechanism for account search
- Supports up to 100 accounts
- Comprehensive menu system

**Operations:**
1. Add Account
2. Deposit
3. Withdraw
4. Check Balance
5. Exit

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Java compiler (javac)
- Command line interface or IDE (Eclipse, IntelliJ IDEA, NetBeans)

## How to Run

### Compilation
```bash
javac <filename>.java
```

### Execution
```bash
java <classname>
```

### Example:
```bash
# For Array-Based System
javac BankWork.java
java BankWork

# For Interface-Based System
javac test.java
java test

# For Scanner Class Implementation
javac bankInternal.java
java bankInternal
```

## Key Concepts Demonstrated

- **Object-Oriented Programming**: Classes, objects, encapsulation
- **Arrays**: Single and multi-dimensional arrays for data storage
- **Interfaces**: Abstract types and polymorphism
- **Constructors**: Object initialization
- **Input Handling**: BufferedReader, Scanner, DataInputStream
- **Control Structures**: Loops, conditionals, switch statements
- **Exception Handling**: Try-catch blocks
- **Data Validation**: Minimum balance, account number validation

## Common Features Across Implementations

- Account number generation/management
- Balance inquiry
- Deposit functionality
- Withdrawal with balance validation
- Account creation
- User input handling

## Learning Outcomes

By studying these implementations, you will learn:

1. Different approaches to solving the same problem
2. Input/output operations in Java
3. Array manipulation and object arrays
4. Interface implementation and polymorphism
5. Constructor usage and object initialization
6. Menu-driven program design
7. Basic exception handling
8. Data validation techniques


## License

This project is for educational purposes. Feel free to use and modify for learning.

## Author

Educational resource for learning Java programming concepts.

-Developed By Tejushree BM

---

**Note**: Each implementation is standalone and can be run independently. Choose the one that best suits your learning objectives or use case.
