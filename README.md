#Expense Tracker
---
This is a simple Core Java project that tracks personal expenses, manages categories, and monitors monthly budgets.

##What It Dose
---
-Takes expense details (Amount, Category, Date, Description) as input
- Saves and loads data automatically from CSV files
- Lets you edit, delete, and view all recorded expenses
- Filters expenses by Category and by Month (YYYY-MM)
- Calculates category-wise spending breakdown with percentages
- Alerts the user when the monthly budget limit is exceeded

##Files
---
- `ExpenseTrackerApp.java` → Main application entry point
- `ConsoleUI.java` → Interactive console menu and user interface
- `ExpenseService.java` → Business logic, Stream filtering, and budget calculations
- `ExpenseRepository.java` → Handles reading and saving to CSV and text files
- `Expense.java` → Model class representing a single expense record
- `expenses.csv` → Data storage file for all expense transactions
- `budget.txt` → Data storage file for the monthly budget limit
- `run.bat` → 1-click script to compile and run the project

##How to Run
---
1. Open the project folder in VS Code then click on run then open in Integrated Terminal.
2. Run the application using the batch script:
run.bat
3. Select any option from 1 to 7 to start managing your expenses!
---
## Built With:
- Java ☕
- Core Java (OOP, Collections & Stream API) - VS Code
