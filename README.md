# SWYNEX Internship — Task 2: Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project was completed as part of my **Data Analyst Internship at SWYNEX Technologies**.

The objective was to perform Exploratory Data Analysis (EDA) on the cleaned e-commerce retail transactions dataset prepared in Task 1. The analysis focuses on understanding sales performance, product categories, customer ratings, payment preferences, order statuses, and geographical patterns.

The project demonstrates how data analysis can transform raw transaction records into meaningful insights that support data-driven business decisions.

## 🎯 Objectives

- Explore and understand the cleaned dataset.
- Calculate descriptive statistics and key sales metrics.
- Identify trends, patterns, and potential anomalies.
- Analyze product categories, payment methods, and order statuses.
- Examine geographical sales distribution and customer ratings.
- Create visualizations to communicate findings.
- Document at least five actionable, data-driven insights.

## 🛠️ Tools and Technologies

- **Python** — Data analysis and calculations
- **Pandas** — Data manipulation and aggregation
- **NumPy** — Numerical analysis
- **Matplotlib & Seaborn** — Data visualization
- **Jupyter Notebook / Google Colab** — Interactive analysis
- **GitHub** — Project documentation and version control

## 📂 Project Structure

```text
SWYNEX-Task-2-EDA/
│
├── SWYNEX_Task_2_EDA.ipynb
├── EDA_Report.md
├── insights.md
├── dataset_profile.json
├── descriptive_statistics.csv
├── category_summary.csv
├── payment_method_summary.csv
├── order_status_summary.csv
├── monthly_sales_summary.csv
├── country_summary.csv
├── product_summary.csv
├── city_summary.csv
├── ecommerce_retail_transactions_cleaned.csv
│
└── charts/
    ├── 01_net_sales_by_category.png
    ├── 02_monthly_net_sales.png
    ├── 03_transactions_by_payment.png
    ├── 04_order_status_distribution.png
    ├── 05_customer_rating_distribution.png
    └── 06_top_countries_net_sales.png
```

## 📊 Dataset Overview

The cleaned dataset contains **11,814 transaction records and 13 original columns**, covering the period from January 2024 to June 2026.

Key fields include:

- `order_id` and `customer_id`
- `order_date`
- `product_category` and `product_name`
- `quantity` and `unit_price_usd`
- `discount_percent`
- `payment_method`
- `shipping_city` and `country`
- `order_status`
- `customer_rating`

The dataset contains transaction, product, payment, location, order-status, and customer-rating information.

## 🔍 Analysis Performed

### 1. Data Profiling and Descriptive Statistics
- Reviewed dataset dimensions, data types, missing values, and duplicate records.
- Calculated descriptive statistics for numerical variables.
- Examined the coverage of customer ratings and shipping-city information.

### 2. Sales Analysis
- Calculated estimated gross sales, discounts, and net sales.
- Compared estimated sales across product categories.
- Summarized monthly sales patterns.
- Identified leading products and geographical markets.

### 3. Customer and Transaction Analysis
- Compared payment-method preferences.
- Examined order-status distribution.
- Analyzed available customer ratings and highlighted missing-data limitations.

### 4. Data Visualization
Created charts to make the findings easier to interpret, including category sales, monthly sales, payment methods, order statuses, customer ratings, and leading countries.

## 💡 Key Findings

The analysis produced the following findings:

1. **Sales performance:** Estimated gross sales were approximately **$1.50 million**, with estimated discounts of **$102.51K** and estimated net sales of **$1.40 million**.
2. **Product categories:** Electronics contributed approximately **27% of estimated net sales**, making it the leading category by this measure.
3. **Payment preferences:** Cash on Delivery was the most frequently used payment method, accounting for approximately **17.3% of transaction records**.
4. **Geographical performance:** The United Arab Emirates contributed approximately **15.1% of estimated net sales** among the countries represented.
5. **Customer feedback:** The average recorded customer rating was approximately **3.90 out of 5**, calculated only from records with available ratings.
6. **Data completeness:** Approximately **50.5% of customer ratings** and **4.2% of shipping-city values** were missing, limiting some customer-experience and city-level analyses.
7. **Discount impact:** Estimated discounts totaled approximately **$102.51K**, equivalent to around **6.83% of estimated gross sales**.

These findings describe the supplied dataset and should not automatically be generalized to all e-commerce businesses.

## 💰 Sales Calculation Method

The analysis uses the following estimates:

- **Estimated Gross Sales** = Quantity × Unit Price
- **Estimated Discount Amount** = Estimated Gross Sales × Discount Percentage ÷ 100
- **Estimated Net Sales** = Estimated Gross Sales − Estimated Discount Amount

These calculations are estimates based on the available columns. They do not independently account for taxes, shipping charges, refunds, returns, or other adjustments unless those are already reflected in the dataset.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Open `SWYNEX_Task_2_EDA.ipynb` in Jupyter Notebook or Google Colab.
3. Ensure the cleaned CSV is available in the expected location.
4. Install any missing dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

5. Run the notebook cells in order.
6. Review the charts, summary tables, and findings.

## 📈 Business Value

This project demonstrates how exploratory analysis can help businesses:

- Identify high-performing product categories and markets.
- Understand transaction and payment-method patterns.
- Monitor sales performance over time.
- Assess customer-feedback coverage.
- Recognize data-quality limitations before making business decisions.

## 🚀 Skills Demonstrated

`Python` · `Pandas` · `NumPy` · `EDA` · `Data Cleaning` · `Descriptive Statistics` · `Data Visualization` · `Business Insights` · `Data Quality Assessment`

## 👨‍💻 About Me

**Shubham Umesh Raut**

M.Sc. Statistics | B.Sc. Mathematics

Aspiring Data Analyst with an interest in statistical analysis, business intelligence, and data-driven decision-making.

- **LinkedIn:** https://www.linkedin.com/in/shubham-raut-986bb1227/
- **GitHub:** https://github.com/shubhamraut0209

---

*This project was completed as part of my Data Analyst Internship at SWYNEX Technologies.*

