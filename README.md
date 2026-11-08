# 🛒 Exploratory Data Analysis of Retail Transactions

## 📊 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on retail transaction data to uncover meaningful patterns, trends, and relationships in customer purchasing behavior and sales performance.

The analysis covers **100,000 retail transactions** across multiple product categories, payment methods, product IDs, and store locations.

The project uses **Python, Pandas, NumPy, Matplotlib, Seaborn, and Plotly** to demonstrate a complete data analysis workflow — from data exploration and cleaning to statistical analysis, visualization, and business insights.

---

## 📁 Dataset Overview

- **Total Records:** 100,000 transactions
- **Original Features:** 10 columns
- **Final Features:** 15 columns after feature engineering
- **Product Categories:** Books, Clothing, Electronics, Home Decor
- **Payment Methods:** Cash, Credit Card, Debit Card, PayPal
- **Product IDs:** A, B, C, D
- **Transaction Period:** April 2023 – April 2024

### Key Dataset Attributes

- Customer ID
- Product ID
- Quantity
- Price
- Transaction Date
- Payment Method
- Store Location
- Product Category
- Discount Applied (%)
- Total Amount

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Plotly** – Interactive visualizations
- **Jupyter Notebook**
- **VS Code**

---

## 🔄 Data Preparation & Cleaning (Python)

- Loaded and explored the retail transaction dataset using `pandas`.
- Inspected dataset structure using `.info()` and `.describe()`.
- Checked missing values across all columns.
- Verified and handled missing values when necessary.
- Checked for duplicate records and confirmed data consistency.
- Converted `TransactionDate` into datetime format.
- Extracted additional date-related features:
  - Year
  - Month
  - Month Name
  - Day
  - Day Of Week
- Standardized column names and categorical values.
- Performed final data quality checks.

**Final Dataset:**
- 100,000 records
- 15 columns
- 0 missing values
- 0 duplicate records

---

## 📊 Exploratory Data Analysis (EDA)

Performed comprehensive univariate, bivariate, and multivariate analysis to understand retail sales patterns.

### 1. Univariate Analysis

- Analyzed numerical variables such as Quantity, Price, Discount Applied (%), and Total Amount.
- Examined categorical distributions across product categories, payment methods, and product IDs.
- Studied transaction amount distribution.
- Identified purchasing quantity patterns.

### 2. Bivariate Analysis

- Analyzed relationships between Quantity and Total Amount.
- Compared Discount Percentage with Total Amount.
- Examined sales performance across product categories.
- Compared total sales and average transaction amounts across payment methods.

### 3. Multivariate Analysis

- Created pivot tables to analyze sales by Product Category and Payment Method.
- Performed correlation analysis between numerical variables.
- Examined category-wise sales performance.
- Analyzed monthly and weekday sales patterns.

---

## 📈 Key Business Insights

### Product Category Analysis

- **Books** generated the highest total sales, approximately **6.26 million**.
- Clothing recorded the highest transaction count, with **25,056 transactions**.
- Home Decor recorded the lowest total sales, approximately **6.17 million**.
- Sales distribution was relatively balanced across all four categories.

### Payment Method Analysis

- **PayPal** recorded the highest total sales, approximately **6.22 million**.
- PayPal was also the most frequently used payment method, with 25,067 transactions.
- Debit Card transactions recorded the highest average transaction amount.
- Overall sales differences between payment methods were relatively small.

### Monthly Sales Analysis

- **July 2023** recorded the highest sales among complete months, approximately **2.13 million**.
- February 2024 recorded the lowest sales among complete months, approximately **1.97 million**.
- December 2023 and January 2024 also recorded relatively high sales.
- Monthly sales remained relatively stable throughout the observation period.

### Day-of-Week Analysis

- **Thursday** recorded the highest total sales, approximately **3.60 million**.
- Saturday recorded the highest transaction count, with 14,354 transactions.
- Monday recorded the lowest total sales.
- Tuesday recorded the lowest transaction count.

### Correlation Analysis

- Quantity and Total Amount showed a moderately positive correlation of **0.6918**.
- Price and Total Amount showed a positive correlation of **0.6363**.
- Discount Percentage and Total Amount showed a very weak negative correlation of **-0.0879**.
- Quantity and Price had almost no linear correlation.

### Customer Transaction Analysis

- Average purchase quantity: **5.01 items**.
- Average product price: **55.07**.
- Average discount: **10.02%**.
- Average transaction amount: **248.33**.
- Median transaction amount: **200.37**.

---

## 📊 Data Visualization

Created multiple visualizations using Matplotlib, Seaborn, and Plotly to communicate analytical findings.

Key visualizations include:

- Product Category Distribution
- Total Sales by Product Category
- Payment Method Distribution
- Distribution of Transaction Amounts
- Transaction Amount by Product Category
- Quantity Purchased Distribution
- Quantity vs Total Amount
- Discount vs Total Amount
- Monthly Sales Trends
- Correlation Heatmap
- Category-wise Sales by Payment Method
- Product ID-wise Total Sales
- Average Discount by Product Category
- Total Sales by Day of the Week

An interactive monthly sales trend visualization was also developed using Plotly.

---

## 💡 Strategic Recommendations

Based on the analysis:

1. **Monitor Product Category Performance:** Regularly evaluate category-wise sales to identify high-performing and low-performing categories.

2. **Optimize Discount Strategies:** Analyze the relationship between discounts and transaction amounts before changing discount policies.

3. **Track Product-Level Performance:** Monitor sales across Product IDs A, B, C, and D to identify differences in product performance.

4. **Analyze Sales Trends:** Use monthly and weekday sales patterns to support future business planning.

5. **Evaluate Payment Methods:** Monitor customer payment preferences and maintain convenient payment options.

6. **Investigate High-Value Transactions:** Examine unusually high transaction amounts to understand their characteristics and ensure data accuracy.

7. **Focus on High-Performing Categories:** Continue monitoring the Books category because it generated the highest total sales.

8. **Implement Regular Reporting:** Develop periodic reports to monitor sales, transaction quantities, discounts, and product performance.

9. **Extend Business Analysis:** Incorporate profit margins, inventory information, and additional store-level data for deeper insights.

10. **Support Data-Driven Decisions:** Use analytical findings as a foundation for evidence-based business strategies.

---

## 🚀 Project Outcome

This project demonstrates:

- Strong understanding of Exploratory Data Analysis (EDA).
- Practical experience in data cleaning and preprocessing.
- Ability to perform univariate, bivariate, and multivariate analysis.
- Knowledge of statistical analysis and correlation.
- Experience creating meaningful data visualizations.
- Ability to identify sales trends and business patterns.
- Skills in translating raw transactional data into actionable business insights.

---

## 📎 Files Included

- Retail Transaction Dataset (CSV)
- Exploratory Data Analysis Jupyter Notebook (`.ipynb`)
- Data Visualizations and Statistical Analysis

---

## 📬 Author

**Dinukrishna A**

---
