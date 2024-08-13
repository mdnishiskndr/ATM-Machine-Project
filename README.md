# MEBENG ATM Machine

This individual course project is developed to fulfill CSC404 requirement This project is designed to developed an ATM Machine using C++ programming language in Dev-C++ Software that can allow user to create a bank account and use it to withdraw money, deposit money and request their balance.

## Table of Content
- [Features](#Features)
- [Installation and Setup](#Installation-and-Setup)
- [File Structure](#File-Structure)
- [Usage Flow](#Usage-Flow)

## Features
- **Create Account:** Register a new account with a username, password, and initial balance.
- **Login:** Access your account by logging in with your username and password.
- **Check Balance:** View the current balance of your account.
- **Deposit Money:** Add money to your account.
- **Withdraw Money:** Withdraw money from your account.

## Installation and Setup

### 1. Clone Repository:
```bash
git clone https://github.com/yourusername/MEBENG-ATM-Machine.git
cd MEBENG-ATM-Machine
```

### 2. Compile the program:
```bash
g++ -o ATM main.cpp
```

### 3. Run the executable:
```bash
./ATM
```

## File Structure

### `main.cpp`
This file contains the main logic of the program.

### `Registered BankAcc.txt`
This text file is used to store user credentials such as *user ID*, *password*, and *initial balance* after registration.

### `Existing BankAcc.txt`
This text file is used as a temporary storage file during the operations of *requesting balance*, *depositing money*, and *withdrawing money*.

## Usage Flow
### 1. Introductory Menu:
- `l -> Login`
- `c -> Create New Account`
- `q -> Quit`
  
Enter the corresponding character to choose an option.

### 2. Create Account:
- Enter your *user ID*, *password*, and *initial balance* when prompted.
- The account details will be saved to `Registered BankAcc.txt`.

### 3. Login:
- Enter your *user ID* and *password*
- If the credentials match, you'll be granted access and presented with the main menu.

### 4. Main Menu:
- `d -> Deposit Money`
- `w -> Withdraw Money`
- `r -> Request Balance`
- `q -> Quit`

Enter the corresponding character to choose an option.

### 5. Request Balance:
- View the current balance of your account.

### 6. Deposit Money:
- Enter the amount to deposit. The balance will be updated accordingly.

### 7. Withdraw Money:
- Enter the amount to withdraw. If sufficient balance is available, the transaction will be completed.


### Interface Output:
![image](https://github.com/user-attachments/assets/a1c3802c-d5ca-40e4-8d99-06d45e890a80)
