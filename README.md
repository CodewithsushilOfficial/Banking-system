# Bank Account System using C and File Handling

This repository contains a simple implementation of a bank account system using C language and file handling in C. The system allows users to create bank accounts, transfer money between accounts, check balances, and log in securely.

## Approach

The bank account system is implemented using a modular approach, with different functions for each operation. Here's an overview of the main functions:

1. **Account Creation (`account()`):** Allows users to create a new bank account by providing personal details such as name, address, date of birth, etc. The account details are stored in a file using file handling functions.

2. **Money Transfer (`transfermoney()`):** Enables users to transfer money from their account to another user's account. Users need to provide the recipient's username and the amount to transfer. Transfer records are stored in a separate file.

3. **Check Balance (`checkbalance()`):** Allows users to check their account balance. The function reads transfer records from the file and calculates the total balance for the specified user.

4. **Login (`login()`):** Provides secure login functionality for users. Users enter their username and password, which are then verified against the stored credentials in the file.

## Implementation

The system is implemented using C programming language and utilizes file handling concepts for data storage. Each function is designed to perform a specific task within the banking system, ensuring modularity and ease of maintenance.

Below is a summary of the key functions implemented in the program:

- **Account Creation (`account()`):** This function collects user input for creating a new account and stores the data in a file named `username.txt`.
  
- **Money Transfer (`transfermoney()`):** Users can transfer money from their account to another user's account by providing the recipient's username and the amount to transfer. Transfer details are recorded in a file named `mon.txt`.
  
- **Check Balance (`checkbalance()`):** Users can check their account balance, and the function retrieves transfer records from `mon.txt` to calculate the total balance for the user.
  
- **Login (`login()`):** Provides a secure login mechanism where users enter their username and password. The function verifies the credentials against stored data in `username.txt` and grants access upon successful authentication.

## Usage

To use the bank account system:

1. Compile the C program using a C compiler.
2. Run the compiled executable file.
3. Follow the on-screen prompts to create a new account, transfer money, check balance, or log in.

## Credits

This project was developed by [Sushil kumar kushwaha](https://github.com/CodewithsushilOfficial).

Feel free to contribute to this project by submitting bug fixes or enhancements via pull requests.

For detailed implementation code, please refer to the `bank_system.c` file in this repository.
