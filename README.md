# E-Commerce-Sales-Customer-Insights-Dashboard-using-Power-BI
# 📊 E-Commerce Sales Dashboard – Power BI

## 📌 Project Overview
This project analyzes e-commerce sales data to identify trends in sales, customer behavior, product performance, and order status using Power BI.

## 🛠 Tools Used
- Power BI
- DAX
- Power Query
- Excel / CSV
- GitHub

## 📂 Dataset
- 10,000 e-commerce transactions
- Includes customer, product, order, and review data

## 📈 Key KPIs
- Total Sales
- Total Orders
- Total Customers
- Average Order Value (AOV)
- Average Rating

## 📊 Dashboard Insights
- Sales trend over time
- Category-wise performance
- Country-wise sales distribution
- Order status analysis
- Customer ratings analysis

## 🧮 Key DAX Measures
```DAX
Total Sales = 
SUMX(
    ecommerce,
    ecommerce[quantity] * ecommerce[unit_price]
)

AOV = DIVIDE([Total Sales], [Total Orders])
