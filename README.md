# Banking-Management-System
Overview
This is a simple banking system application developed in C using the Windows API. The application allows users to perform various banking operations such as creating accounts, depositing money, withdrawing money, checking account balances, updating passwords, viewing transaction histories, and deleting accounts.

Features
Create Account: Allows users to create new bank accounts with an account number, name, and password.
List Accounts: Displays a list of all existing accounts with their account numbers, names, and balances.
Deposit Money: Allows users to deposit money into their accounts.
Withdraw Money: Allows users to withdraw money from their accounts.
Check Balance: Displays the current balance of a specified account.
Update Password: Allows users to update the password of their accounts.
View Transactions: Displays the transaction history of a specified account.
Delete Account: Allows users to delete their accounts.
Getting Started
Prerequisites
Windows operating system
A C compiler that supports the Windows API (e.g., MinGW, Visual Studio)
Installation
Clone the repository or download the source code.
Open the project in your preferred C development environment.
Compile the source code to generate the executable.
Usage
Run the executable file generated after compilation.
Use the graphical user interface to perform various banking operations.
File Structure
accounts.dat: Stores account information.
transactions.dat: Stores transaction history.
main.c: Contains the source code for the banking system application.
Functions
create_account: Creates a new account and saves it to the accounts.dat file.
list_accounts: Lists all accounts from the accounts.dat file.
deposit_money: Deposits money into a specified account.
withdraw_money: Withdraws money from a specified account.
check_balance: Checks the balance of a specified account.
update_password: Updates the password of a specified account.
view_transactions: Views the transaction history of a specified account.
delete_account: Deletes a specified account.
validate_account: Validates the account number and password.
log_transaction: Logs transactions to the transactions.dat file.
show_error_message: Displays error messages.
clear_input_fields: Clears the input fields in the UI.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.


Acknowledgments
This application was developed as a learning project to understand the Windows API and file handling in C.
Contact
For any questions or feedback, please contact the project maintainer.
