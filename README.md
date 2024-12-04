# Finance Tracker

A Python-based Finance Tracker to log, analyze, and visualize financial transactions. This application allows users to track their income and expenses, view transaction summaries within a date range, and visualize data trends over time.

---

## Features

1. **Add Transactions**  
   - Log financial transactions with details like date, amount, category (Income or Expense), and a brief description.

2. **View Transaction Summary**  
   - Filter and display transactions within a specified date range.
   - Summarize total income, total expenses, and net savings for the selected period.

3. **Visualize Data**  
   - Generate line plots of income and expenses over time.

4. **Data Persistence**  
   - All transactions are stored in a CSV file (`finance.csv`) for easy retrieval and long-term storage.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/finance-tracker.git
   cd finance-tracker
2. Install the required Python packages:
   ```bash
   pip install pandas matplotlib
3. (Optional) Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
---

## File Structure

1. **main.py**
   - The main entry point for the application.

2. **finance.csv**
   - The CSV file where all transaction data is stored.

3. **data_entry.py**
   - Utility functions to handle user input (like date, amount, category, description
---

## License

-- This project is licensed under the MIT License. See LICENSE for more details.

---

### Customize as Needed:
- Replace `"https://github.com/your-username/finance-tracker.git"` with the actual repository link.
- Update the license information if applicable.




