# Credit Card Validator

## Overview
This program validates credit card numbers using the **Luhn Algorithm**. It checks if the entered credit card number is valid based on a set of rules defined by the algorithm. The program is written in C++ and provides a simple console interface for user interaction.

## Features
- Validates credit card numbers using the Luhn Algorithm.
- Handles user input and provides feedback on validity.
- Allows users to exit the program at any time by typing "exit".

## How It Works
1. **Input**: The user is prompted to enter a credit card number.
2. **Validation**: The program checks if the input consists only of digits. If not, it prompts an error message.
3. **Luhn Algorithm**:
   - Doubles every second digit from the right, summing the digits if the result is greater than 9.
   - Adds all other digits (those not doubled).
   - Checks if the total sum is divisible by 10 to determine validity.

## Requirements
- C++ compiler (e.g., g++, Visual Studio)
- Basic understanding of how to run console applications
