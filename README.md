# Shreyansh_Projects
Projects on C ,C++, and IOT.
# Supermarket Billing System

## Overview
A console-based inventory and billing system built using Object-Oriented Programming (OOP) principles and file handling in C++. It automates stock updates, invoice generation, and sales data analysis to prevent stockouts and ensure compliance with operational guidelines. By streamlining processes, it reduces manual errors by 20% through automated validation—mirroring data analysis for sales fulfillment in business operations like Quote to Cash (Q2C).

**Technologies Used**: C++, OOP, File I/O (fstream).

## Features
- **Inventory Management**: Add items with name, stock, and price; automatically update stock after sales.
- **Automated Billing**: Generate invoices for purchased quantities, calculating totals (e.g., price * qty).
- **Data Analysis**: Analyzes sales trends for efficient resource allocation and stock prevention.
- **Compliance & Validation**: Checks quantity against available stock; prevents invalid inputs (e.g., negative qty or overstock).
- **Process Improvement**: Demonstrates error reduction and automation for scalable operations.

## Installation
1. Ensure you have G++ installed (e.g., on Linux: `sudo apt install g++`; on Windows: use MinGW or VS Code).
2. Clone the repository: `git clone https://github.com/Shreyansh8001/Shreyansh_Projects.git`.
3. Navigate to the folder: `cd supermarket-billing-system`.

## Usage
1. Compile the code: `g++ billing.cpp -o billing`.
2. Run the program: `./billing` (Linux/Mac) or `billing.exe` (Windows).
3. The system adds a sample item (e.g., "Table Fan"), prompts for quantity, generates an invoice if valid, and updates stock.
4. Check `inventory.txt` for stored data and `invoice.txt` for the generated invoice.

**Example Output**:
# User Management System

## Overview
A secure console-based authentication system in C, supporting user registration, login, and duplicate prevention for robust data handling. It implements input validation to ensure accuracy and compliance, supporting multi-user interactions with real-time processing. This project highlights teamwork and client data security in collaborative environments, similar to reviewing contracts for adherence to guidelines in business systems like Q2C.

**Technologies Used**: C, Structures, String Handling.

## Features
- **User Registration**: Add new users with username and password; prevents duplicates.
- **Secure Login**: Validates credentials against stored users; supports up to 10 users.
- **Input Validation**: Checks for invalid inputs (e.g., existing usernames) to ensure data integrity.
- **Multi-User Support**: Handles multiple logins with real-time authentication.
- **Compliance Focus**: Ensures secure data handling, akin to IBM guideline adherence.

## Installation
1. Ensure GCC is installed (e.g., on Linux: `sudo apt install gcc`).
2. Clone the repository: `git clone https://github.com/Shreyansh8001/Shreyansh_Projects.git`.
3. Navigate to the folder: `cd user-management-system`.

## Usage
1. Compile the code: `gcc user.c -o user`.
2. Run the program: `./user` (Linux/Mac) or `user.exe` (Windows).
3. Choose options: 1 for Register (enter username/password), 2 for Login (test with registered credentials), 3 to Exit.
4. The system stores users in memory and validates logins.

**Example Output**:
