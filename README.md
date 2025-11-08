# 💰 Expense-tracker

A personal finance dashboard built with **Streamlit**, **Pandas**, and **Plotly** to help you categorize, visualize, and analyze your income and expenses from bank statements in CSV format.

---

## 📌 Overview

The **Simple Finance Dashboard** is a web-based tool that allows you to:

- Upload your bank transaction CSV files.
- Automatically categorize expenses based on saved keywords.
- Manually reassign categories using an editable table.
- Track your total expenses and payments.
- Visualize expenses by category using a pie chart.
- Persist category rules using a local `categories.json` file.

---

## 🚀 Features

### ✅ File Upload
- Upload transaction files in CSV format.
- Columns automatically cleaned and formatted.

### 📂 Expense Categorization
- Automatically tags transactions using keywords.
- Allows manual category changes.
- Add new categories directly from the UI.
- Keywords are saved for future sessions.

### 📊 Visualizations & Metrics
- Expense summary table by category.
- Interactive pie chart for expense breakdown.
- Total payments summary for credits.

---

## 📁 CSV File Format

Ensure your CSV file includes these columns:

| Column         | Description                        |
|----------------|------------------------------------|
| `Date`         | Date in `DD MMM YYYY` format       |
| `Details`      | Description of the transaction     |
| `Amount`       | Transaction amount (e.g., 1,000.50)|
| `Debit/Credit` | Must be either `Debit` or `Credit` |

## 🛠️ Technologies Used

- **Streamlit** – Web interface
- **Pandas** – Data processing
- **Plotly** – Visualizations
- **JSON** – Persistent storage for categories
