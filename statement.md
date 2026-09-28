Project Statement
Currency Converter 
1. Introduction

The Currency Converter System is a Python-based application designed to perform currency conversions between different currencies. The project provides a simple, menu-driven interface that allows users to convert currencies, view exchange rates, check conversion history, and obtain basic information about supported currencies.

2. Problem Statement

Converting an amount from one currency to another manually can be time-consuming and may result in calculation errors. This project aims to provide a simple and efficient application that performs currency conversion automatically using predefined exchange rates.

3. Objective

The main objectives of this project are:

To develop a simple currency conversion application using Python.

To allow users to convert amounts between multiple currencies.

To display exchange rates based on USD.

To maintain a history of successful conversions during program execution.

To provide basic information about supported currencies.

To demonstrate fundamental Python programming concepts.

4. Scope of the Project

The system supports the following currencies:

USD — US Dollar

INR — Indian Rupee

EUR — Euro

GBP — British Pound

JPY — Japanese Yen

AUD — Australian Dollar

CAD — Canadian Dollar

CNY — Chinese Yuan

The system uses predefined exchange rates stored in a Python dictionary. The rates can be modified directly in the source code when required.

5. Working of the System

The user is presented with a main menu containing the following options:

Convert Currency

View Exchange Rates

View Conversion History

Currency Information

View Available Currencies

Exit

When the user selects the currency conversion option, they enter:

Source currency code

Target currency code

Amount to convert

The program first converts the source currency into USD and then converts the USD amount into the target currency.

6. Conversion Formula

The application uses the following formulas:

USD Amount = Entered Amount / Source Currency Rate

Target Amount = USD Amount × Target Currency Rate


For example, if:

1 USD = 88 INR


then:

100 USD = 100 × 88
        = 8800 INR

7. Technologies Used

The project is developed using:

Programming Language: Python 3

Data Structures: Dictionary and List

Programming Concepts: Functions, loops, conditional statements, input/output, and string operations.

8. Functional Requirements

The system should be able to:

Display all supported currencies.

Accept source and target currency codes.

Accept the amount to be converted.

Perform currency conversion.

Display the conversion result.

Display predefined exchange rates.

Store successful conversions in history.

Display conversion history.

Display information about a selected currency.

Exit the application safely.

9. Validation Requirements

The application validates user input by:

Checking whether the source currency code is valid.

Checking whether the target currency code is valid.

Preventing negative amounts.

Checking whether the selected menu option is valid.

10. Limitations

The current version of the project has some limitations:

Exchange rates are predefined and are not obtained from a live API.

Conversion history is available only while the program is running.

History is not stored permanently.

The application uses a command-line interface.

Invalid text entered where a numeric amount is expected can cause an input error.

11. Future Enhancements

The system can be improved by adding:

Live exchange rates through an API.

Support for additional currencies.

A graphical user interface.

Permanent storage of conversion history.

CSV or database support.

Date and time for each conversion.

Better exception handling.

Currency symbols and improved formatting.

12. Conclusion

The Currency Converter System demonstrates how Python can be used to create a practical application using basic programming concepts. It provides currency conversion, exchange-rate viewing, history management, and currency information through a simple menu-driven interface.

This project helps demonstrate the practical use of Python dictionaries, lists, functions, loops, conditional statements, and user input in developing a real-world application.
