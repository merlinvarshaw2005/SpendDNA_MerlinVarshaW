README — SpendDNA: Personal Spending Analysis

📌 Project Overview

SpendDNA is a personal spending analysis project developed to analyse transaction data and generate meaningful insights about spending behaviour.

The project takes a transaction dataset as input, cleans and processes the data using Python, and produces a structured spending report containing financial summaries, spending categories, vendors, monthly trends, spending patterns, anomalies, and spending archetypes.

The project is designed to help users understand where their money is being spent, which vendors/categories contribute most to expenses, and what patterns exist in their spending behaviour.


---

🎯 Objectives

The main objectives of SpendDNA are:

Analyse personal transaction data.

Calculate total transactions, credits and debits.

Identify unique vendors.

Identify uncategorised transactions.

Analyse spending by category.

Identify the highest-spending vendors.

Analyse food-delivery spending patterns.

Analyse monthly spending trends.

Detect unusual/high-value transactions.

Identify personal spending archetypes.

Generate meaningful financial insights from transaction data.



---

🛠️ Technologies Used

Python

Google Colab

Pandas — data cleaning and analysis

NumPy — numerical calculations

CSV/Excel — transaction data source



---

📂 Dataset

The project uses a transaction dataset containing information such as:

Date

Transaction Type

Amount

Vendor

Category

Description


The dataset used in this project contains approximately 1,310 transactions.

The dataset is processed programmatically rather than manually calculating the results.


---

🔄 Project Workflow

Transaction Dataset
        ↓
Data Loading
        ↓
Data Cleaning
        ↓
Column Standardisation
        ↓
Transaction Processing
        ↓
Credit / Debit Analysis
        ↓
Category Analysis
        ↓
Vendor Analysis
        ↓
Time & Monthly Analysis
        ↓
Anomaly Detection
        ↓
Spending Archetypes
        ↓
Key Insights
        ↓
SpendDNA Report


---

📊 Analysis Performed

1. Executive Summary

The report calculates:

Total credits

Total debits

Net change

Savings rate

Total transactions

Unique vendors

Uncategorised transactions



---

2. Top Categories

Transaction expenses are grouped by category to determine:

Highest-spending categories

Percentage contribution of each category

Total amount spent per category


This helps identify the major areas contributing to overall spending.


---

3. Top Vendors

Vendor-level analysis identifies:

Highest-spending vendors

Total amount spent at each vendor

Number of transactions/orders associated with each vendor



---

4. Time-of-Day Patterns

The project analyses transaction timing to identify spending patterns such as:

Food-delivery activity

Late-night food transactions

Café-related spending

Quick-commerce activity



---

5. Monthly Trend

The project groups transactions by month to show how spending changes over time.

For example:

Jan 2024
Feb 2024
Mar 2024
Apr 2024
...

Food-delivery spending is also analysed month-by-month.


---

6. Anomaly Detection

The project identifies unusually large transactions using a standard-deviation-based approach.

Transactions that are significantly different from the normal spending pattern can be highlighted as potential anomalies.

The report displays detected anomalies along with:

Date

Vendor

Amount

Z-score



---

7. Spending Archetypes

Based on the spending patterns, the project identifies behavioural categories such as:

The Foodie

The Quick Commerce User

The Shopaholic

The Investor

The Late-Night Snacker

The YOLO Spender


These archetypes provide an easy-to-understand interpretation of the transaction data.


---

📈 Final Output

The final SpendDNA report contains:

SpendDNA Report

Executive Summary
        ↓
Top Categories
        ↓
Top Vendors
        ↓
Time-of-Day Patterns
        ↓
Monthly Trend
        ↓
Top Anomalies
        ↓
Spending Archetypes
        ↓
Key Insights

The output is generated directly from the uploaded transaction dataset.


---

💡 Key Benefits

Converts raw transaction data into understandable information.

Helps identify major spending categories.

Highlights frequently used vendors.

Shows monthly spending behaviour.

Identifies unusual transactions.

Provides an easy-to-understand spending personality.

Reduces the need for manual financial analysis.



---

🚀 How to Run the Project

Step 1 — Open Google Colab

Open a new Google Colab notebook.

Step 2 — Upload the Dataset

Upload the transaction CSV/Excel file when prompted.

Step 3 — Run the Python Program

Run the complete SpendDNA analysis program.

Step 4 — Generate the Report

The program automatically processes the dataset and prints the final SpendDNA report.


---

📁 Project Structure

SpendDNA/
│
├── dataset/
│   └── transactions.csv
│
├── SpendDNA.ipynb
│
└── README.md


---

🔮 Future Enhancements

The current project focuses on Python-based transaction analysis. Possible future improvements include:

Interactive dashboard

AI-generated financial recommendations

Automatic expense categorisation

Spending prediction

Budget recommendations

Interactive charts

Web-based user interface

Monthly budget alerts



---

👩‍💻 Project Status

Status: Completed / Working Prototype

The current implementation successfully loads the transaction dataset, performs data processing and analysis, and generates the targeted SpendDNA printed report.


---

📜 Conclusion

SpendDNA transforms raw transaction records into a structured personal spending report. By combining transaction processing, category analysis, vendor analysis, monthly trends, anomaly detection, and spending archetypes, the project provides a clear view of spending behaviour and helps users understand their financial patterns.

SpendDNA — Understand your spending. Discover your spending DNA.
