# Walmart_data_Analysis
# 🛒 Walmart Sales Analysis - SQL + Python Project

This project is focused on analyzing Walmart's sales dataset using **Python** for data cleaning and **SQL (MySQL Workbench)** for querying and extracting business insights.

## 📂 Dataset

- Sourced from [Kaggle](https://www.kaggle.com/datasets).
- Contains fields like: invoice ID, branch, city, category, unit price, quantity, date, time, payment method, rating, profit margin, and total.

## 🔧 Tools Used

- Python (for cleaning, transforming)
- Pandas, NumPy
- MySQL Workbench
- Kaggle API

## 🧼 Data Cleaning Steps (Python)

- Loaded raw data using Pandas
- Checked nulls, data types
- Converted `date` and `time` into datetime format
- Exported clean data and imported into MySQL table: `walmart_sales`

## 📊 SQL Analysis Performed

1. **Total transactions per payment method**
2. **Revenue comparison between 2022 and 2023**
3. **Most preferred payment method per branch (using CTE + RANK)**
4. **Shift-wise invoice distribution: Morning, Afternoon, Evening**
5. **Top-rated category in each branch (using Window Function)**
6. **Busiest day in each branch**
7. **City-wise rating insights (min, max, avg)**
8. **Top 5 branches with highest revenue drop from 2022 to 2023**


Key Insights
E-wallet was the most popular payment method across most branches.

Evening is the busiest time for purchases.

Some branches saw a noticeable revenue drop in 2023 vs 2022.

Health and Beauty had one of the highest-rated categories in certain branches.
