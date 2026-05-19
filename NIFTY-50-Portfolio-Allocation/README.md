# 📈 NIFTY 50 Portfolio Allocation System

A Python-based portfolio allocation project that builds an equal-weight investment portfolio using live stock market data from Yahoo Finance.

This project fetches real-time stock information, calculates equal investment allocation for each stock, and exports the final portfolio into a professionally formatted Excel spreadsheet.

---

## 🚀 Features

* 📊 Fetches live stock data using Yahoo Finance API
* 💹 Calculates equal-weight portfolio allocation
* 🏢 Extracts company sector and market capitalization
* 🧮 Computes the number of shares to purchase
* 📁 Exports results to Excel with formatting
* ✅ User-friendly and beginner-friendly project structure

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* yFinance
* XlsxWriter
* Jupyter Notebook

---

## 📂 Project Structure

```bash
├── nifty50.csv
├── portfolio_allocation.ipynb
├── README.md
```

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/nifty50-portfolio-allocation.git
```

Move into the project directory:

```bash
cd nifty50-portfolio-allocation
```

Install required libraries:

```bash
pip install pandas numpy yfinance xlsxwriter
```

---

## ▶️ How to Run

1. Open the Jupyter Notebook:

```bash
jupyter notebook
```

2. Run all cells step by step.

3. Enter your portfolio investment amount when prompted.

4. The final portfolio will be exported as:

```bash
portfolio.xlsx
```

---

## 📊 Workflow

```text
Load NIFTY 50 CSV
        ↓
Fetch Live Stock Data
        ↓
Create Portfolio DataFrame
        ↓
Calculate Equal Allocation
        ↓
Determine Shares to Buy
        ↓
Export Excel Report
```

---

## 📸 Example Output

The exported Excel file contains:

* Stock Symbol
* Sector
* Current Price
* Market Capitalization
* Number of Shares to Buy

---

## 💡 Concepts Used

This project demonstrates:

* API Data Collection
* Data Cleaning & Processing
* Financial Data Analysis
* Portfolio Management Basics
* Excel Automation
* Python Data Structures

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---