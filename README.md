# Supermarket Sales Analysis

## Project Overview
Supermarket Sales Analysis is a data analytics project that studies 500 supermarket sales transactions. The project identifies sales patterns across products, branches, categories, customer types, payment methods, and customer ratings.

## Problem Statement
The aim of this project is to analyze supermarket sales data and find useful information that can support inventory planning, branch performance analysis, customer understanding, and business decision-making.

## Dataset
The dataset contains 500 sales transactions with fields such as Invoice ID, Date, Branch, City, Customer Type, Gender, Product, Category, Quantity, Unit Price, Payment, Rating, and Sales.

**Dataset link:** https://docs.google.com/spreadsheets/d/1QIX__4VObHFMEXnRM2xJyXmB5JAB2peHrJcQ41_U9TE/edit?usp=sharing

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- OpenPyXL for reading the Excel dataset

## Analysis Performed
1. Loaded the Excel dataset.
2. Checked the dataset structure, data types, missing values, and duplicate rows.
3. Validated Sales using Quantity × Unit Price.
4. Calculated total and average transaction sales.
5. Analyzed product-wise sales.
6. Compared branch-wise sales.
7. Analyzed category-wise sales.
8. Counted payment-method usage.
9. Compared average spending by customer type.
10. Calculated the average customer rating.
11. Created charts for the major findings.

## Key Results
- Highest-sales product: **Cheese — ₹27,906.30**
- Highest-performing branch: **Branch C (Mumbai) — ₹72,469.45**
- Highest-sales category: **Beverages — ₹56,108.24**
- Most-used payment method: **UPI — 127 transactions**
- Average Member transaction: **₹483.14**
- Average Normal customer transaction: **₹497.07**
- Average customer rating: **3.99 / 5**

## Project Files
- `Anusha_Supermarket_Sales_Analysis.ipynb` — complete Jupyter Notebook/code
- `requirements.txt` — required Python libraries
- `Anusha_ProjectReport.docx` — project report
- `README.md` — project overview and setup instructions

## Setup and Run Instructions
1. Install Python 3.x.
2. Download or clone the project files.
3. Place `SUPER MARKET DATA.xlsx` in the same folder as the notebook.
4. Install the dependencies:

```bash
pip install -r requirements.txt
```

5. Start Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Anusha_Supermarket_Sales_Analysis.ipynb` and run the cells from top to bottom.

## Business Decisions
The supermarket can maintain sufficient stock of high-selling products and categories, study the practices contributing to Branch C's performance, continue supporting widely used payment methods such as UPI, and use customer-rating results to identify areas for service improvement. Customer spending patterns can also be considered when designing membership offers.

## Conclusion
This project shows how transaction data can be transformed into clear visual and numerical insights that can support practical supermarket business decisions.
