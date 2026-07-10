# 🪔 Diwali Sales Data Analysis Using Python

An exploratory data analysis (EDA) project that uncovers customer purchase behavior and sales trends from Diwali festive season sales data, using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.

## 📌 Overview

This project analyzes retail sales during the Diwali season to understand **who is buying, what they're buying, and where they're buying from**. The analysis covers customer demographics (gender, age, marital status, occupation) and sales patterns (state, product category, top-selling products) to surface insights that can inform business and marketing decisions.

## 🗂️ Repository Contents

| File | Description |
|------|-------------|
| `Diwali_Sales_Data.csv` | Raw sales dataset with customer and order details |
| `Diwali_Sales_Analysis.ipynb` | Jupyter Notebook with data cleaning, EDA, and visualizations |

## 🧰 Tools & Libraries

- **Python**
- **Pandas** — data cleaning and manipulation
- **NumPy** — numerical operations
- **Matplotlib** & **Seaborn** — data visualization
- **Jupyter Notebook**

## 🧹 Data Cleaning Steps

- Dropped unrelated/blank columns (`Status`, `unnamed1`)
- Removed null/missing values
- Converted `Amount` column to integer type
- Renamed and inspected columns for consistency

## 📊 Exploratory Data Analysis

The notebook explores sales patterns across:

- **Gender** — purchase count and total amount spent by gender
- **Age Group** — buyer distribution and spending power by age and gender
- **State** — top 10 states by number of orders and total sales
- **Marital Status** — spending patterns of married vs. unmarried customers
- **Occupation** — buyer count and spending by profession
- **Product Category** — most purchased categories and top-selling products

## 📈 Key Insights

- **Women** make up the majority of buyers and also have higher purchasing power than men.
- Most buyers fall in the **26–35 years** age group, dominated by females.
- **Uttar Pradesh, Maharashtra, and Karnataka** lead in both order volume and total sales.
- **Married women** are the largest spending segment.
- Buyers are largely employed in **IT, Healthcare, and Aviation** sectors.
- **Food, Clothing, and Electronics** are the top-selling product categories.

## 🚀 How to Use

1. Clone or download this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open `Diwali_Sales_Analysis.ipynb` in Jupyter Notebook / JupyterLab / VS Code.
4. Run the cells sequentially to reproduce the cleaning, analysis, and visualizations.

## 📁 Dataset Fields

`User_ID`, `Cust_name`, `Product_ID`, `Gender`, `Age Group`, `Age`, `Marital_Status`, `State`, `Zone`, `Occupation`, `Product_Category`, `Orders`, `Amount`
## 📫 Connect With Me

- LinkedIn: [www.linkedin.com/in/sahilkhan-data]
- Email: [mdsahil0624@gmail.com]
- GitHub: [https://github.com/sahilkhan-data]
Than you
