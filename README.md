# Semester_Project
GYASI OSEI
UEB3223622
Title: Simple Console Banking System

Description:
The "OG Banking System" is a basic console application that simulates a simple banking system. It allows users to perform a set of banking operations, including opening accounts, making deposits, withdrawing funds, and generating account statements. The application operates in a loop, enabling users to perform multiple operations before choosing to exit.

Features:

Open Account: Users can open an account by providing their first name, last name, date of birth, account number, and initial balance. The account number must be unique.

Deposit: Users can deposit funds into their accounts by entering their first name, last name, and account number. If the account details match, the user can input the amount to deposit.

Withdraw: Users can withdraw funds from their account if they have a sufficient balance. They need to enter their first name, last name, and account number to proceed with the withdrawal.

Generate Account Statement: Users can generate an account statement by providing their first name, last name, and account number. After accounting for deposits and withdrawals, the statement displays the account holder's name and the remaining balance.

Exit: Users can choose to exit the program, ending the loop and terminating the application.

Implementation:

The project uses a simple structure named date to store day, month, and year components for dates.
It employs a do-while loop that presents a menu of options to the user.
Depending on the selected option, the user is prompted to provide relevant information for the chosen operation.
The program checks the validity of provided inputs and performs the specified operation if the conditions are met.
The loop continues until the user chooses to exit by selecting option 5.
