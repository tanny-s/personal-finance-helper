# Finance Tracker 💰

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

## Project Description
The Finance Tracker is a Python-based application designed to help users manage their personal finances by tracking income and expenses. Users can:

- Add new transactions with details such as date, amount, category (Income/Expense), and description.
- View detailed transaction history within a specified date range.
- Generate summaries of income, expenses, and net savings.
- Visualize financial data through plotted graphs.

---

## Features ✨
- **Transaction Tracking**: Add and manage income/expense records.
- **Custom Date Range**: Filter and view transactions for specific periods.
- **Financial Summary**: Get an overview of total income, expenses, and net savings.
- **Data Visualization**: Generate graphs to visualize financial trends over time.

---

## Requirements 🛠️
To run the Finance Tracker application, ensure you have:

- Python 3.x installed on your system.
- Required libraries:
  - `pandas`: For data manipulation.
  - `matplotlib`: For data visualization.
  - `csv`: For handling CSV file operations.

Install the required libraries using:
```bash
pip install pandas matplotlib
```

---

## Usage Instructions 🏃‍♂️

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-repository>/finance-tracker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd finance-tracker
   ```

3. Run the main script:
   ```bash
   python main.py
   ```

### Application Workflow
1. **Main Menu Options**:
   - Add a new transaction.
   - View transactions and summary within a date range.
   - Exit the application.

2. **Adding Transactions**:
   - Enter the date of the transaction (or press Enter for today’s date).
   - Enter the transaction amount.
   - Specify the category as Income or Expense.
   - Provide an optional description.

3. **Viewing Transactions and Summary**:
   - Enter the start and end dates for the range.
   - View all transactions, total income, total expenses, and net savings for the specified range.
   - Optionally generate a graph showing income and expense trends.

---

## Code Overview 🔍

### Main Components
1. **`main.py`**:
   - Manages the main workflow, including the user menu and options.
   - Provides functionality for adding transactions, viewing history, and plotting graphs.

2. **`data_entry.py`**:
   - Contains utility functions for user input handling (date, amount, category, description).
   - Ensures valid and user-friendly data entry.

3. **`finance_data.csv`**:
   - A CSV file used to store transaction data persistently.
   - Automatically created if not present.

### Key Functionalities
- **Adding Transactions**:
   Transactions are appended to `finance_data.csv` with fields:
   - `date`, `amount`, `category`, `description`.

- **Viewing Transactions**:
   Filter transactions by date range and calculate financial summaries (total income, total expenses, net savings).

- **Data Visualization**:
   Generate time-series plots for income and expenses using `matplotlib`.

---

## Example Usage 🧪

### Adding a Transaction
```bash
1. Add a new transaction
Enter the date of the transaction (dd-mm-yyyy) or press Enter for today's date: 01-01-2025
Enter the amount: 5000
Enter the category ('I' for Income or 'E' for Expense): I
Enter a description (optional): Freelance work
Entry added successfully.
```

### Viewing Transactions and Summary
```bash
2. View transactions and summary within a date range
Enter the start date (dd-mm-yyyy): 01-01-2025
Enter the end date (dd-mm-yyyy): 31-01-2025
Transactions from 01-01-2025 to 31-01-2025:

      date  amount category      description
01-01-2025   5000   Income  Freelance work

Summary:
Total Income: $5000.00
Total Expense: $0.00
Net Savings: $5000.00

Do you want to see a plot? (y/n): y
```

---

## Contribution 🤝
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a Pull Request.

---

## License 📜
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact 📧
For inquiries, contact the team:
- **Tanmay Bhupendra Sonawane**: [tanmaysonawane007@gmail.com](mailto:tanmaysonawane007@gmail.com)
- **Mayur Ramchandra Ranode**: [mayurranode7@gmail.com](mailto:mayurranode7@gmail.com)
- **Prathmesh Ravindra Dhekane**: [prathmesh2003dhekane@gmail.com](mailto:prathmesh2003dhekane@gmail.com)
- **Tanishka Amit Pansare**: [tanishkapansare5555@gmail.com](mailto:tanishkapansare5555@gmail.com)

