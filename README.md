# E-Commerce-Sales-analysis-for-Data-Driven-Making
# 🛍️ E-Commerce Sales Data Cleaning & Analysis (2019–2024)

This project involves cleaning, exploring, and analyzing a real-world Amazon sales dataset spanning six years (2019–2024). The goal is to extract key business insights from structured e-commerce transaction data.

---

## Dataset Overview

- **File**: `amazon_sales_dataset_2019_2024_corrected.xlsx`
- **Format**: Excel (.xlsx)
- **Total Records**: 5,000 rows after cleaning
- **Features**: 15 columns including:
  - Order ID, Order Date, Customer ID, Product Name
  - Product Category, Quantity Sold, Unit Price
  - Discount (%), Total Sales, Profit Margin, Region
  - Payment Method, Salesperson, Order Status

---

## 🔧 Data Cleaning & Preprocessing

### Cleaning Actions Taken:
- Removed duplicate rows
- Standardized `Order Date` to datetime format
- Converted `Unit Price`, `Quantity Sold`, and `Total Sales` to numeric
- Filtered out negative price records
- Removed titles (Mr., Dr., PhD) from `Customer Name`
- Replaced or removed invalid/blank values in `Region`
- Verified data types across all columns

### Issues Identified:
- Duplicates
- Missing Region and Price fields
- Inconsistent date formatting
- Customer names with titles
- Negative/invalid Unit Prices

---

## Key Columns Used for Analysis

| Column          | Use Case                            |
|-----------------|--------------------------------------|
| Order Date      | Time-series trend analysis           |
| Customer ID     | Segmentation and behavior tracking   |
| Product Name    | Best-seller identification           |
| Quantity Sold   | Sales volume trends                  |
| Total Sales     | Revenue analytics                    |
| Region          | Geographic performance evaluation    |
| Order Status    | Completion vs cancellation analysis  |

---

## Insights Summary

### Regional Sales
- **Top Region**: South America – $1.2M+
- Followed by: Asia, Europe, Australia, North America
-  *South America shows strongest market performance*

### Product Volume
- **Top-Selling Product**: “Present” with 98 units sold
- Other high performers: 86, 78, 75, 72 units

### Customer Insights
- Top 10 customers each contribute ~9–11% of total revenue
- **Top Buyer**: Jennifer Wright (highest total sales)

---

## Deliverables

- `cleaned_sales_dataset.csv`: Cleaned data for analysis
- `data_cleaning_report.pdf`: Data issues & cleaning steps
- `pivot_charts.png`: Sales trends & performance visuals
- `README.md`: Project overview and documentation

---

## Technologies Used

- Python (Pandas, NumPy)
- Excel
- Jupyter Notebook

---

## Conclusion

This cleaned and validated dataset is now ready for:
- Sales trend analysis
- Customer segmentation
- Regional performance evaluation
- Building dashboards or predictive models

---
