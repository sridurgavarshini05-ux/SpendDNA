# SpendDNA - Personal Spending Analyzer

## Project Overview

SpendDNA analyzes six months of synthetic transaction data
from January to June 2024 using Python, Pandas and NumPy.

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab

## Features

1. Transaction Parser - cleans dates, amounts and duplicates.
2. Vendor Extractor - identifies vendors.
3. Category Tagger - categorizes transactions.
4. Spending Overview - calculates credits, debits and top expenses.
5. Monthly Analysis - examines monthly spending trends.
6. Time-of-Day Analysis - analyzes transaction timing.
7. Anomaly Detection - flags unusual transactions using z-scores.
8. Spending Archetypes - identifies spending behaviors.

## Dataset

- Period: January to June 2024
- Cleaned transactions: 1,310
- Unique vendors: 47
- Dataset: rahul_transactions.csv

## Key Findings

- Total credits: Rs. 509,774
- Total debits: Rs. 1,678,901
- Largest spending category: E-commerce (35.97%)
- Highest-spending month: March 2024
- Anomalies detected: 24
- Spending archetypes: Shopaholic and YOLO Spender

## How to Run

1. Open SpendDNA.ipynb in Google Colab.
2. Upload rahul_transactions.csv.
3. Run all notebook cells in order.
4. Review the results and final report.

## Project Files

- SpendDNA.ipynb
- rahul_transactions.csv
- SpendDNA_Report.txt
- README.md

## Limitations

The dataset is synthetic. Anomalies are statistically unusual
transactions, not necessarily fraud.

Net cash flow includes investments, transfers and cash withdrawals
as debits and should not be interpreted as actual savings.

## AI-Use Disclosure

ChatGPT was used to assist with understanding Python and Pandas,
developing and debugging code, and formatting the final report.
The code was run and the results were reviewed in Google Colab.
