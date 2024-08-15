# Daily-Usage-Tracker

This project is a simple command-line personal finance tracker that allows users to manage their transactions, categorize them as income or expenses, and visualize their financial data over time. It uses Python with the `pandas`, `csv`, and `matplotlib` libraries to handle data storage, manipulation, and visualization.

## Features

- **Add New Transactions**:
  Users can enter the date, amount, category (Income/Expense), and description of a transaction. If no date is provided, today's date is used by default.

- **View Transactions and Summary**:
  Users can view transactions within a specified date range. The summary includes total income, total expenses, and net savings.

- **Plot Transactions**:
  Optionally, users can visualize their income and expenses over time using a line plot.

## Files

- `finance_data.csv`:
  A CSV file used for storing transaction data.

- `data_entry.py`:
  A module providing functions to get user input for date, amount, category, and description.

- `finance_tracker.py`:
  The main script for managing transactions, displaying summaries, and plotting data.
  
- `requirement.txt`:
  To install required dependencies to execute the project.

## Dependencies

- `pandas`
- `matplotlib`

You can install these dependencies using pip:

```bash
pip install pandas matplotlib
```
## To execute the project use below command:
```bash
python3 main.py
```




