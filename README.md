# Supermarket Sales & Profit Analysis

## Project Overview
This project presents a complete sales and gross-income analysis for supermarket transaction data.

## Problem Statement
Analyze supermarket transactions to evaluate sales performance, gross-income trends, product and branch performance, customer behavior, payment patterns, and time-based sales trends, then provide actionable recommendations.

## Objectives
- Measure key business KPIs from transaction data
- Analyze sales and gross income across branches, products, and customer groups
- Study payment preferences and time-based demand patterns
- Generate practical, evidence-based recommendations

## Dataset
- Source: https://www.kaggle.com/datasets/lovishbansal123/sales-of-a-supermarket
- Place dataset at: `data/supermarket_sales.csv`

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook
- python-docx

## Project Structure
```text
supermarket-sales-analysis/
│
├── data/
│   └── supermarket_sales.csv
│
├── AnubhutiJha_SupermarketSalesAnalysis.ipynb
├── requirements.txt
├── AnubhutiJha_ProjectReport.docx
└── README.md
```

## Features
- Data cleaning (missing values, duplicates, date/time conversion, feature extraction)
- KPI analysis (sales, gross income, quantity, transactions, ATV, rating)
- Sales and gross-income analysis by branch/city/product/customer/payment/time
- Customer and payment behavior comparison
- Ten required business visualizations
- Auto-generated key insights and recommendations from actual results

## Installation
```bash
pip install -r requirements.txt
```

## Dataset Setup
1. Download the CSV from the Kaggle link above.
2. Place it at:
   `data/supermarket_sales.csv`

## How to Run
```bash
jupyter notebook
```
Then open and run:
`AnubhutiJha_SupermarketSalesAnalysis.ipynb`

## Analysis Performed
- Dataset overview and preprocessing
- KPI calculation
- Sales analysis by branch, city, product line, customer type, gender, payment, month, day, hour
- Gross-income analysis by branch, product line, customer type, gender, and month
- Product, branch, customer, payment, and time-based performance review

## Key Insights (from current dataset in repository)
1. Total sales are **4175.72** and total gross income is **198.84** from **10** transactions.
2. **Branch A** has the highest sales (**2522.76**) and gross income (**120.13**), while **Branch B** is lowest.
3. **Electronic accessories** is the top product line by sales (**1141.53**) and gross income (**54.36**).
4. **Food and beverages** is the lowest product line by sales (**172.75**) and gross income (**8.23**).
5. **Normal** customers contribute more sales (**2455.12**) than **Member** customers (**1720.60**).
6. **Ewallet** dominates payment contribution with **3506.09** sales (~**83.96%** of total sales).
7. Sales peak in **February** (**2013.20**), on **Sunday** (**1601.95**), and at **13:00** (**1062.24**).

## Recommendations
1. Replicate operational practices from Branch A in lower-performing branches, especially Branch B.
2. Keep stronger inventory for Electronic accessories and run promotions for Food and beverages.
3. Run membership-conversion offers targeting higher-spending Normal customers.
4. Continue e-wallet incentives while preserving smooth card/cash options.
5. Align staffing and shelf replenishment around peak demand windows (Sunday, ~13:00, and peak month patterns).

## Conclusion
The project provides a fully executable, beginner-friendly analysis workflow from data cleaning to business recommendations, using historical supermarket transaction data and real computed results.
