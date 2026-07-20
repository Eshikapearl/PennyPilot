# PennyPilot (Python CLI)

## Description

Expense Tracker is a Python command-line application that helps users record and manage their daily expenses. It allows users to keep track of their spending, view summaries, organize expenses into categories, set monthly budgets, and export records for future use.

## Features

* ## Features

* Add expenses
* Update expense records
* Delete expenses
* View all expenses
* Generate total and monthly summaries
* Categorize and filter expenses
* Set monthly budgets
* Receive budget alerts
* Export data to CSV
* Store data using JSON


## Requirements

* Python 3.8 or later
* No external libraries required (uses Python's built-in libraries)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/expense-tracker.git
   ```
2. Open the project folder:

   ```bash
   cd expense-tracker
   ```
3. Run the application:

   ```bash
   python expense_tracker.py
   ```

## Usage

Example commands:

```bash
python expense_tracker.py add --description "Lunch" --amount 20 --category Food

python expense_tracker.py list

python expense_tracker.py update --id 1 --amount 25

python expense_tracker.py delete --id 1

python expense_tracker.py summary

python expense_tracker.py summary --month 7

python expense_tracker.py budget --amount 500

python expense_tracker.py export
```

## Real-Life Applications

* Track daily personal expenses
* Monitor monthly spending habits
* Plan and manage budgets effectively
* Identify major spending categories
* Maintain financial records for future reference
* Export spending reports for analysis or documentation

