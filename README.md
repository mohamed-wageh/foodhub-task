# foodhub-task

# **Expense Tracker App**
A React Native application for managing personal expenses. Users can add, view, edit, and delete expenses, with an intuitive UI for efficient expense management.

## Features
- Add Expenses: Input the amount, date, and description for each expense.
- Edit/Delete Expenses: Manage existing expenses directly from the list.
- Expense Summary: View total expenses for a specific period.
- Input Validation: Ensures all fields are correctly filled out.
- Theming: Consistent and customizable styles using a centralized global theme.

## Tech Stack
- Frontend: React Native & Expo
- Styling: React Native StyleSheet with a Global Style System.
- Navigation: React Navigation (for managing screens like ManageExpense).
- State Management: Local state management with hooks like useState.

## Folder Structure
### /components
- Contains reusable UI components.
- ExpensesOutput/:
- ExpensesSummary: Displays a summary of expenses for a given period.
- ExpensesList: Renders a list of expenses.
- ExpenseItem: Displays a single expense item.
- ManageExpense/:
- ExpenseForm: Form for adding or editing an expense.
- Input: Customizable input fields for the form.
### UI/:
- Button: Custom button component with styles and modes.
### /constants
- Defines the global styles for theming, such as colors.
### /util
- Contains utility functions, such as getFormattedDate for date formatting.

## Installation
### Clone the repository:
git clone https://github.com/your-repo/expense-tracker.git
### Install dependencies:
npm install
### Start the development server:
npm start

## How to Use
- Home Screen: Displays all expenses in a list, grouped by the selected period.
- Add Expense: Click on the Add button to create a new expense.
- Edit/Delete Expense: Tap on any expense item to edit or delete it.
- Summary: The summary bar at the top shows total expenses for the selected period.

## Known Issues

## Ensure all fields are filled correctly to avoid validation errors.
## Dates must follow the YYYY-MM-DD format
