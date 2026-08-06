# Sales Data Analysis 📊

## Overview

This project analyzes sales data to identify trends, product performance, and customer insights.

## Tools Used

- Excel
- SQL
- Python (Pandas)
- Power BI

## Objectives

- Clean and analyze sales data
- Find sales trends
- Identify top-performing products
- Generate meaningful insights

## 🛠️ Step-by-Step Implementation Process

### Step 1: Data Preparation & Calculated Fields
- Analyzed the raw sales transaction dataset (`sales_data`).
- Created a calculated field for **Revenue** using the Excel formula: `=Quantity * Price` (`=E2*F2`).
- Formatted values into appropriate data types (Currency, Numbers, Dates).

### Step 2: Key Metric Calculations (KPIs)
- **Total Revenue:** Calculated using `=SUM(Revenue_Column)`.
- **Total Units Sold:** Calculated using `=SUM(Quantity_Column)`.
- **Total Orders:** Calculated using `=COUNTA(Order_ID_Column)`.

### Step 3: Data Aggregation with PivotTables
Built four separate PivotTables on a dedicated backend tab (`pivot_data`):
1. **Sales by Category:** Sum of Revenue grouped by Product Category.
2. **Sales by Region:** Sum of Revenue grouped by Region.
3. **Sales by Product:** Revenue contribution per individual product.
4. **Quantity Sold by Product:** Total volume sold per item.

### Step 4: Visual Dashboard Design
- Created 4 matching PivotCharts (Pie, Column, and Bar charts).
- Transferred all charts to a separate, clean **`Dashboard`** presentation sheet.
- Arranged charts into a symmetrical 2x2 grid layout.
- Removed background sheet gridlines for a polished, presentation-ready finish
