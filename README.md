# Credit Card Validator

## Overview

This is a simple C++ program that uses the Luhn Algorithm to validate credit card numbers. The program prompts the user to input a credit card number and then determines whether it's a valid credit card number or not.

## Luhn Algorithm

The Luhn Algorithm, also known as the "modulus 10" or "mod 10" algorithm, is a simple checksum formula used to validate a variety of identification numbers, especially credit card numbers.

The algorithm works as follows:

1. Starting from the rightmost digit (the check digit) and moving left, double the value of every second digit.
2. If doubling a digit results in a two-digit number, add the digits of that number together.
3. Sum all the digits, including the ones that were not doubled.
4. If the total sum is a multiple of 10, the credit card number is valid; otherwise, it's invalid.

## Usage

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/swetamishra123/Credit-Card-Validator.git
    ```

2. Compile the C++ program using a C++ compiler.

    ```bash
    g++ main.cpp -o main
    ```

3. Run the program:

    ```bash
    ./main
    ```

4. Follow the on-screen instructions to enter credit card numbers for validation. You can exit the program by typing 'exit'.

## Example Output

