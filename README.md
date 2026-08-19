# Retail Sales Performance Dashboard

## Project Overview

This project analyzes a retail sales dataset to identify revenue trends, product/category performance, customer purchasing behavior, and payment-method patterns. The project combines Python/Jupyter Notebook for data cleaning and analysis with Microsoft Power BI for interactive dashboard development.

## Objectives

- Analyze overall retail sales performance
- Identify monthly revenue trends
- Analyze product/category performance
- Analyze customer purchasing behavior
- Analyze payment-method usage
- Build an interactive Power BI dashboard
- Generate actionable business insights

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Power BI
- GitHub

## Project Workflow

```text
Retail Sales Dataset
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis
        ↓
KPI Analysis
        ↓
Trend & Category Analysis
        ↓
Business Insights
        ↓
Interactive Power BI Dashboard
        ↓
GitHub Documentation
```

## Data Cleaning & Preprocessing

The dataset was processed using Python/Jupyter Notebook. The workflow included:

- Inspecting dataset structure
- Checking missing values
- Checking duplicate records
- Cleaning column names
- Converting date fields
- Validating numerical fields
- Creating useful date-based features
- Exporting a cleaned dataset for Power BI

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Sales | 1.53M |
| Total Transactions | 12.362K |
| Total Customers | 25 |
| Average Transaction Value | 123.49 |

## Dashboard Features

The Power BI dashboard contains:

- Total Sales KPI
- Total Transactions KPI
- Total Customers KPI
- Average Transaction Value KPI
- Monthly Sales Trend
- Sales by Category
- Sales by Payment Method
- Year filter
- Category filter
- Payment Method filter

## Business Insights

### Revenue Trends

January was the strongest month in the displayed annual trend, with approximately **148.8K** in sales. October was the weakest month, with approximately **119.4K**.

The variation indicates that sales demand changes significantly throughout the year. The business should investigate the factors behind strong months and use those findings to improve weaker periods.

### Category Performance

**Butchers** was the highest-performing category in the dashboard, generating approximately **204K** in sales.

Milk Products and Patisserie were among the lower-performing categories. These categories could be evaluated for targeted promotions, product bundling, cross-selling, pricing, and inventory improvements.

### Payment Method Analysis

Payment methods were relatively balanced:

| Payment Method | Share |
|---|---:|
| Cash | 34.72% |
| Credit Card | 32.68% |
| Digital Wallet | 32.60% |

No single payment method dominates the displayed sales distribution. Maintaining all three payment options is therefore appropriate.

### Customer Purchasing Behavior

The dataset contains **25 unique customers** and **12.362K transactions**, indicating substantial transaction activity relative to the number of customers.

A deeper customer analysis should consider total spending per customer, transaction frequency, and average transaction value per customer.

## Actionable Recommendations

1. Investigate the factors responsible for January's high sales performance and determine whether successful practices can be repeated.
2. Analyze weaker categories and use targeted promotions rather than applying discounts across all products.
3. Protect inventory availability for high-performing categories such as Butchers.
4. Increase average transaction value through bundles, cross-selling, and complementary-product recommendations.
5. Continue supporting Cash, Credit Card, and Digital Wallet payments because their usage is relatively balanced.
6. Perform deeper customer-level analysis to identify high-value and repeat customers.

## Dataset Limitation

The current dataset does not provide sufficient geographic information such as region, state, or city. Therefore, genuine regional sales analysis cannot be performed from this dataset without introducing unsupported data.

## Repository Structure

```text
retail-sales-performance-dashboard/
│
├── data/
│   ├── raw/
│   │   └── retail_store_sales.csv
│   └── processed/
│       └── retail_store_sales_cleaned.csv
│
├── notebooks/
│   └── retail_sales_analysis.ipynb
│
├── powerbi/
│   └── Retail_Sales_Performance_Dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
├── reports/
│   └── business_insights.md
│
├── README.md
└── .gitignore
```

## Dashboard Preview

Add your final Power BI dashboard screenshot to the `screenshots` folder and reference it here:

```markdown
![Retail Sales Performance Dashboard](screenshots/dashboard.png)
```

## Conclusion

The project demonstrates an end-to-end retail sales analytics workflow, from data cleaning and exploratory analysis in Python to KPI analysis and interactive visualization in Power BI. The resulting dashboard helps identify revenue trends, category performance, payment behavior, and opportunities for improving sales performance.

## Author

**Shubham Fulwani**

