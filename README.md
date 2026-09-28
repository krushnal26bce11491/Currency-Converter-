 Currency Converter

A simple Python-based Currency Converter System developed as a college project.
The program allows users to convert amounts between different currencies, view exchange rates, check conversion history, and get basic currency information.

📌 Features

Convert between multiple currencies

View available currencies

View exchange rates based on USD

View conversion history

Get information about a selected currency

Input validation for invalid currency codes

Prevents negative amounts

Simple menu-driven interface

Conversion results are rounded to 2 decimal places

💻 Technologies Used

Python 3

Python dictionaries

Functions

Lists

Loops

Conditional statements

User input/output

💰 Supported Currencies

The application currently supports:

Code	Currency	Rate Based on 1 USD
USD	US Dollar	1.00
INR	Indian Rupee	88.00
EUR	Euro	0.85
GBP	British Pound	0.74
JPY	Japanese Yen	147.00
AUD	Australian Dollar	1.52
CAD	Canadian Dollar	1.38
CNY	Chinese Yuan	7.12

Note: The exchange rates in this project are fixed values stored in the Python program. They are not automatically updated from live exchange-rate data.

🚀 How to Run
1. Install Python

Make sure Python 3 is installed on your computer.

You can check by running:

python --version


or:

python3 --version

2. Save the Program

Save the Python code in a file such as:

currency_converter.py

3. Run the Program

Open a terminal or command prompt in the project directory and run:

python currency_converter.py

🖥️ Main Menu

When the program starts, it displays the following menu:

==========================================
       CURRENCY CONVERTER SYSTEM
==========================================
1. Convert Currency
2. View Exchange Rates
3. View Conversion History
4. Currency Information
5. View Available Currencies
6. Exit
==========================================

🔄 Currency Conversion

Select option 1 to convert a currency.

Example:

Enter source currency code: USD
Enter target currency code: INR
Enter amount: 100


Output:

==========================================
             CONVERSION RESULT
==========================================

100.0 USD = 8800.0 INR

==========================================


The program first converts the source currency into USD and then converts USD into the target currency.

Conversion Formula
USD Amount = Amount / Source Currency Rate

Converted Amount = USD Amount × Target Currency Rate


For example:

100 USD × 88 INR = 8800 INR

📊 View Exchange Rates

Select option 2 to display the exchange rates.

Example:

Exchange rates based on 1 USD:
------------------------------------------
1 USD = 1.0 USD
1 USD = 88.0 INR
1 USD = 0.85 EUR
1 USD = 0.74 GBP
1 USD = 147.0 JPY
...

📜 Conversion History

Every successful conversion is stored in the program's history list.

Select option 3 to view previous conversions.

Example:

==========================================
           CONVERSION HISTORY
==========================================
1 . 100.0 USD -> 8800.0 INR
2 . 50.0 EUR -> 61.18 USD
==========================================


The history is stored only while the program is running. It is not saved permanently to a file or database.

ℹ️ Currency Information

Select option 4 and enter a currency code.

Example:

Enter currency code for information: INR

------------------------------------------
Currency Code : INR
Currency Name : Indian Rupee
Rate vs USD   : 88.0
------------------------------------------

🌍 Available Currencies

Select option 5 to display all currencies supported by the application.

❌ Exit

Select option 6 to close the program.

The program displays:

Thank you for using Currency Converter!
Program terminated successfully.

🛡️ Input Validation

The application checks:

Whether the source currency exists

Whether the target currency exists

Whether the entered amount is negative

Whether the menu choice is valid

For example:

Invalid source currency!


or:

Amount cannot be negative!

📁 Project Structure

A simple project structure can be:

Currency-Converter/
│
├── currency_converter.py
└── README.md

🎯 Project Objective

The main objective of this project is to demonstrate basic Python programming concepts by developing a practical currency conversion application.

The project demonstrates:

Variables

Dictionaries

Lists

Functions

if-elif-else statements

for loops

while loops

String manipulation

User input

Basic mathematical operations

Input validation

🔮 Future Improvements

The project can be improved by adding:

Live exchange rates using an API

More currencies

Graphical User Interface (GUI)

Permanent conversion history

Date and time for each conversion

Export history to CSV

Better error handling for non-numeric input

Currency symbols

Online exchange-rate updates
