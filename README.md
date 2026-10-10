# 📱 Mobile Sales Analysis Dashboard | Power BI

## Project Overview

The **Mobile Sales Analysis Dashboard** is a data analytics project built with **Microsoft Power BI** to explore mobile phone sales, compare brand and model performance, and understand customer purchasing behavior.

The dashboard summarizes key sales metrics and provides interactive filters for exploring results by month, mobile model, payment method, and brand. The accompanying Excel workbook contains the transaction-level dataset used for the analysis.

## Objectives

- Monitor overall sales performance using key performance indicators (KPIs).
- Analyze the quantity of mobile phones sold and the number of transactions.
- Compare sales across mobile brands and mobile models.
- Explore sales distribution across cities.
- Understand customer payment-method preferences.
- Review customer ratings and rating categories.
- Enable users to filter the dashboard and investigate specific segments.

## Tools & Technologies

- **Microsoft Power BI Desktop** — dashboard creation and data visualization
- **Power Query** — data inspection and preparation, where applicable
- **DAX** — measures and calculated fields used in the report
- **Microsoft Excel** — source dataset

## Dataset

**File:** `Mobile Sales Data.xlsx`  
**Records:** 3,835 transaction rows  
**Columns:** 14

The dataset includes the following fields:

| Column | Description |
|---|---|
| `Transaction ID` | Transaction identifier |
| `Day`, `Month`, `Year` | Transaction date components |
| `Day Name` | Day of the week |
| `Brand` | Mobile phone brand |
| `Units Sold` | Quantity sold in the transaction |
| `Price Per Unit` | Price per unit |
| `Customer Name` | Customer name in the dataset |
| `Customer Age` | Customer age |
| `City` | City associated with the transaction |
| `Payment Method` | Payment method used |
| `Customer Ratings` | Customer rating |
| `Mobile Model` | Mobile phone model |

The dataset contains five brands—Apple, Samsung, OnePlus, Vivo, and Xiaomi—and 15 mobile models. The recorded years range from 2021 to 2024.

## Dashboard Features

### 1. KPI Cards
The report includes summary metrics for:
- Total Sales
- Total Quantity
- Transactions
- Average Price

### 2. Brand and Model Analysis
- Compare performance across mobile brands.
- Review sales by mobile model.
- Use brand and model slicers to focus on selected products.

### 3. City-Level Sales
- Explore sales geographically by city.
- Compare sales performance across the cities represented in the dataset.

### 4. Payment Method Analysis
- Review transaction distribution by payment method.
- Compare UPI, cash, debit card, and credit card transactions.

### 5. Customer Ratings
- Explore customer ratings and rating-status categories to understand the feedback represented in the data.

### 6. Interactive Filters
The dashboard includes slicers for:
- Month
- Mobile Model
- Payment Method
- Brand

These filters help users investigate sales performance for selected time periods and customer or product segments.

## Key Measures

The dashboard uses measures such as `Total_Sales`, `Total_Quantity`, `Transactions`, and `Average_Price`.

Typical business definitions to verify against the report's DAX formulas:

- **Total Sales:** sum of sales value.
- **Total Quantity:** sum of units sold.
- **Transactions:** count of transaction records or distinct transaction IDs, depending on the DAX definition.
- **Average Price:** average price measure as defined in the report.


## Business Questions

This dashboard can help explore questions such as:

- Which brands and mobile models contribute most to sales?
- How does sales performance vary by city?
- Which payment methods are most commonly used?
- How many units are sold and how many transactions are recorded?
- What do customer ratings indicate about the customer experience?
- How do the results change when filtering by month, brand, model, or payment method?


## Skills Demonstrated

- Power BI dashboard development
- KPI reporting
- Data visualization
- Sales and customer analysis
- Working with Excel datasets
- Interactive filtering and report exploration
- Translating business questions into analytical views

## Conclusion

The Mobile Sales Analysis Dashboard provides an interactive overview of mobile sales and customer-related data. It brings key metrics, product comparisons, city-level sales, payment methods, and customer ratings into one report to support data-driven exploration.

---
