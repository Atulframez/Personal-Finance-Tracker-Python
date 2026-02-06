# 💰 Personal Finance Tracker (Python)

Project Overview:
The Personal Finance Tracker is a simple command-line application that helps users track their income, expenses, and savings goals. It also provides visualizations of spending patterns to better understand financial habits. The project uses SQLite for data storage and Matplotlib for creating various financial charts.

## Features:
Add Income: Record income entries with descriptions and amounts.
Add Expense: Record expenses, categorize them, and add descriptions.
View Summary: View a summary of total income, expenses, and balance.
Set Savings Goals: Define and track savings goals.
Visualize Spending: Generate various charts (bar chart, pie chart, line chart, etc.) to better understand your spending habits.

## Technologies Used:
Python: Core programming language.
SQLite3: Local database for storing transaction records.
Matplotlib: Python library for generating visualizations.


To run the program:
1] Clone the repository
2] Navigate to Personal Finance Tracker folder
3] Run the main.py file

When you run the application, a menu will appear with the following options:

Add Income: Enter the amount and description of your income.
Add Expense: Enter the amount, category, and description of the expense.
View Summary: See your total income, expenses, and remaining balance.
Set Savings Goal: Set a savings goal to track progress.
Visualize Spending: Choose from various charts to visualize your spending patterns.

## Install Dependencies
pip install -r requirements.txt

## Usage

Run the application:

python main.py


You will see the following menu:

--- Personal Finance Tracker ---
1. Add Income
2. Add Expense
3. View Summary
4. Set Savings Goal
5. Visualize Spending
6. Exit

## Visualizations Available

Bar Chart – Spending by category
Pie Chart – Expense distribution
Line Chart – Expenses over time
Stacked Bar Chart – Income vs Expenses
Histogram – Expense frequency
All charts are generated using Matplotlib.

## Project Structure
personal-finance-tracker-python/
│
├── main.py            # Main menu & app entry point
├── database.py        # SQLite database setup
├── tracker.py         # Income & expense logic
├── savings.py         # Savings goal tracking
├── visualization.py   # Charts & data visualization
├── requirements.txt
└── README.md

## Learning Outcomes

SQLite database integration in Python

CRUD operations

Modular Python project structure

Data visualization with Matplotlib

Financial data analysis basics

CLI application design

## Future Enhancements

Date-based filtering

Monthly budget limits

Export data to CSV / Excel

GUI or Web interface

User authentication

Cloud database support

## Disclaimer

This project is intended for educational and personal use only.
Financial data should be handled responsibly.

## Author

Atul Anand
BCA (Hons)
Amity University, Noida

##  Support

If you find this project useful, don’t forget to star ⭐ the repository!
