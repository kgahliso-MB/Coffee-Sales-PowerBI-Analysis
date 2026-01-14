# ☕ Coffee Sales Insights Dashboard (Power BI)

## 📌 Project Overview
This project transforms raw vending machine transaction data into a functional business dashboard. The goal was to analyze sales performance, identify peak transaction times, and understand customer purchasing behavior (product preference and payment methods).

## 🛠️ Data Engineering (Power Query)
The raw dataset was provided in a semi-structured CSV format (all data in a single column). I performed the following **ETL (Extract, Transform, Load)** steps:
- **Data Splitting:** Parsed the single-column string into six distinct attributes: `Date`, `DateTime`, `Cash Type`, `Card ID`, `Amount (Money)`, and `Product Name`.
- **Cleaning:** Handled `null` values in the Card ID column by identifying them as "Cash Payments."
- **Data Typing:** Assigned appropriate data types (Fixed Decimal for currency, Date/Time for timestamps) to ensure calculation accuracy.
- **Deduplication:** Removed duplicate transaction logs based on unique timestamps.

## 📊 Key Insights & Visuals
- **Revenue Overview:** KPI cards showing Total Revenue and Total Orders.
- **Product Popularity:** A bar chart ranking the top-selling beverages (Latte vs. Americano vs. 
- **Sales Trends:** A line chart visualizing peak sales hours during the day.

## 🚀 How to Use
1. Download the `Power Bi- Coffee Sales.pbix` file.
2. Open it in **Power BI Desktop**.
3. Use the **Payment Method Slicer** to filter the entire dashboard by Cash or Card.

## 🛠️ Tools Used
- **Power BI Desktop**
- **Power Query (M)**
- **GitHub** (for version control and portfolio)
