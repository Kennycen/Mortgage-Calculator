# Mortgage Calculator

This C++ program calculates mortgage amortization schedules and generates a detailed payment table. The program takes into account loan amount, interest rate, loan term, and additional principal payments.

## Features

- Calculates monthly mortgage payments
- Handles additional principal payments
- Generates amortization schedule
- Formats currency with proper comma separation
- Exports results to a file of your choice

## How to Run

1. **Compile the Code:**
   - Make sure you have a C++ compiler installed (like g++, Visual C++, or Clang)
   - Open terminal/command prompt in the project directory
   - Compile using one of these commands:
     ```bash
     # Using g++
     g++ Mortgage_Calculator.cpp -o mortgage_calculator

     # Using Visual C++
     cl Mortgage_Calculator.cpp
     ```

2. **Run the Program:**
   ```bash
   # On Windows
   mortgage_calculator.exe

   # On Linux/Mac
   ./mortgage_calculator
   ```

3. **Follow the Prompts:**
   - Enter the loan amount when prompted
   - Provide the annual interest rate
   - Input the loan term in years
   - Specify any additional monthly principal payment
   - Enter a filename for the output (e.g., "mortgage.txt")

4. **View Results:**
   - Check the output file you specified for the complete amortization table

## Input Parameters

The program accepts the following inputs:
- Loan amount (0-9,999,999)
- Annual interest rate (0-30%)
- Loan term in years (1-99)
- Additional monthly principal payment (0-9,999,999)
- Output file name

## Sample Input 

- Enter Loan amount (0-9999999), for example 300000.90: 250000
- Enter annual interest rate (0-30), for example 4.5 meaning 4.5%: 4.5
- Enter no. of years as integer (1-99), for example 30: 30
- Enter additional principal per month (0-9999999), for example 300: 200
- Send the mortgage amortization table to a file (enter file name): mortgage.txt

## Sample Output

Below is an example of the generated mortgage.txt file:

MORTGAGE AMORTIZATION TABLE

Amount: $ 250,000.00
Interest Rate: 4.5%
Term (Years): 30
Monthly Payment: $ 1,267.05
Additional Principal: $ 200.00
Actual Payment: $ 1,467.05

