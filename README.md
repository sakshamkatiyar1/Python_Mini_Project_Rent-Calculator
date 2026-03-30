# Python Mini Project: Rent Calculator
# Project Description

The Rent Calculator is a simple Python-based mini project that helps calculate the total amount each person needs to pay when sharing a flat or hostel. It considers rent, food expenses, and electricity charges, and divides the total cost among all individuals.

This project is useful for beginners to understand basic Python concepts such as user input, arithmetic operations, and variables.

# Features
Takes user input for all major expenses
Calculates electricity bill based on units consumed
Divides total expenses among multiple people
Simple and easy-to-understand logic
Beginner-friendly project

# Inputs Required

The program asks the user to enter the following details:

Total rent of the flat/hostel
Total amount spent on food
Total electricity units consumed
Charge per electricity unit
Number of people sharing the space
Output
Displays the amount each person needs to pay

# How It Works
The user enters all the required inputs.

Electricity bill is calculated:

electricity_bill = electricity_spend * charge_per_unit

Total expenses are calculated:

total_expense = rent + food + electricity_bill

Final amount per person:

amount_per_person = total_expense // persons

The result is displayed on the screen.
# Technologies Used
Python (Basic)

## Run the script:

Rent Calculator.py

## Sample Run

Enter your hostel/flat rent = 10000
Enter the amount of food ordered = 2000
Enter the total of electricity spend = 150
Enter the charge per unit = 10
Enter the number of persons living in room/flat = 4

Each person will pay = 3375

## Project Screenshot

![Rent Calculator Output](screenshot.png)
