# CS213-Banking-Project

For this project, we developed a simple software to simulate and process the banking transactions for a bank. The transactions are
entered through the command lines on the terminal. The software is an interactive system to produce the output
whenever a transaction is entered. This software can process transactions of opening an account, closing
an existing account, depositing money to an existing account, withdrawing money from an existing account, and printing
the details of all accounts. Additionally, there are four different types of banking accounts that can be created.

Start the program by running the "RunProject2" file.

Command line examples: 
O C John Doe 2/19/2000 599.99 //opens a checking account
O CC Jane Doe 10/1/2000 999.99 0 //opens a college checking account
O S april march 1/15/1987 1500 1 //opens a savings account
O MM Roy Brooks 10/31/1979 2909.10 //opens a Money Market account

D C John Doe 2/19/1990 100 //deposits money to existing account

W C John Doe 2/19/1990 100 //withdraws money from existing account

P    //displays all the accounts in the account database
PI     // displays all the accounts in the account database with fees and interest
UB    //updates the account balance for all accounts by applying the fees and interests earned.
Q     //terminates the program


