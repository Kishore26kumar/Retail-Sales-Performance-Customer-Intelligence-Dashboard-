# Retail Sales Performance & Customer Intelligence Dashboard

An interactive, three-page Power BI report built to explore retail sales performance, product trends, customer segments, and sales-channel performance.

## Project Overview

This project transforms retail transaction data into an interactive business intelligence dashboard. It brings key performance indicators and detailed product, customer, and channel analysis together so users can explore business performance across selected dates and categories.

## Tools & Technologies

- **Microsoft Power BI Desktop** – report development and data visualization
- **Power Query** – data cleaning and transformation
- **DAX** – business measures and time-intelligence calculations
- **Data Modeling** – relationships between sales, product, customer, and date tables

## Dashboard Pages

### 1. Executive Overview

Provides a high-level view of overall business performance.

- KPI cards: Total Revenue, Total Orders, Total Customers, and Average Order Value
- Monthly revenue trend
- Revenue by product category
- Sales-channel performance
- Interactive date and business-category filters

### 2. Product Performance

Helps identify products and categories contributing to sales.

- Product-level revenue analysis
- Category performance comparison
- Quantity and sales analysis
- Product contribution visualizations

### 3. Customer & Channel Analysis

Explores customer and sales-channel patterns.

- Customer and order KPIs
- Customer-segment analysis
- Regional revenue analysis
- Sales-channel comparison

## Data Preparation & Modeling

- Cleaned and transformed source data using Power Query.
- Organized the model into a sales fact table and supporting Product, Customer, and Date tables.
- Created relationships so report visuals and slicers can filter related data consistently.
- Used a dedicated date table for time-based analysis.

## Key DAX Measures

The report includes business measures such as:

- Total Revenue
- Total Orders
- Total Quantity
- Total Customers
- Average Order Value (AOV)
- Revenue MTD (Month-to-Date)
- Revenue QTD (Quarter-to-Date)
- Revenue YTD (Year-to-Date)
- Previous Year Revenue
- Revenue Growth %

## How to Use

1. Download `SALES_REPORT.pbix` from this repository.
2. Open the file using **Power BI Desktop**.
3. Use the report-page tabs to navigate between the three dashboards.
4. Apply the slicers to filter the report and explore the results.

> **Note:** The report contains the Power BI model and visuals. To refresh the data, ensure the original data source is available and update the data-source settings in Power BI if required.

## Repository Structure

```text
retail-sales-dashboard/
│
├── README.md
├── SALES_REPORT.pbix
└── screenshots/
    ├── executive-overview.png
    ├── product-performance.png
    └── customer-channel-analysis.png
```

Add your own dashboard screenshots to the `screenshots` folder and update the image links below when available.

## Dashboard Previews

### Executive Overview

_Add screenshot: `screenshots/executive-overview.png`_

### Product Performance

_Add screenshot: `screenshots/product-performance.png`_

### Customer & Channel Analysis

_Add screenshot: `screenshots/customer-channel-analysis.png`_

## Business Value

The dashboard helps users monitor core sales KPIs, compare performance over time, identify high-performing products and categories, and explore customer-segment, regional, and channel patterns. These insights can support sales planning and business-performance discussions.

## Author

**Kishore Kumar**

Data Analyst | Power BI | DAX | Power Query
