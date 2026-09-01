# Consignment Store Data Analysis

Power BI analysis of real-world consignment store sales, seasonality, ownership mix, financial performance, and payment trends.

## Overview

This Power BI project analyzes real sales and financial data from a consignment store.

The data came from monthly Excel files. I used Power Query to clean and combine the files, fix data-quality issues, and prepare the data for analysis.

I then built a Power BI data model and created DAX measures to analyze sales, store income, consignor payouts, auction sales, seasonality, ownership type, payment methods, and year-over-year performance.

## Main Business Questions

- How are sales changing over time?
- Which seasons and weekdays perform better?
- How much of sales comes from store-owned and consignment inventory?
- How important are auction sales?
- How are sales distributed between store income, consignor payout, and tax?
- Which payment methods contribute the most to sales?

## Data Preparation

Main tasks included:

- Combining monthly Excel files
- Cleaning inconsistent data
- Standardizing payment methods
- Handling missing and unknown values
- Creating ownership classifications
- Handling changes in the source-file structure
- Finding and correcting source-data issues
- Reconciling sales and income totals
- Creating a Date table for time analysis

## Data Model

The model includes:

- RawFiles for sales data
- Income for financial data
- DateTable for time analysis
- Metrics for DAX measures

RawFiles and Income are both connected to the DateTable.

## Main Measures

Examples include:

- Total Sales
- Store Net Income
- Consignor Payout
- Total Tax Collected
- Average Sales per Sales Day
- Auction Sales %
- Store-owned Sales %
- Previous Year Sales
- YoY %

## Dashboard Pages

### Executive Overview

Shows the main KPIs, monthly sales trend, seasonality, ownership mix, and payment methods.

### Sales Trends and Seasonality

Shows monthly sales trends, previous-year comparison, weekday performance, seasonality, and Sales Day Count.

### Financial Performance

Shows sales distribution, auction performance, ownership type, monthly financial trends, and payment methods.

## Key Insights

- Store-owned inventory represents an important share of sales.
- Consignment inventory generates the larger overall sales amount.
- Weekend performance is generally stronger than several weekdays.
- Sales performance changes across seasons.
- Auction inventory represents a meaningful share of sales.
- VISA is the main payment method by sales value.

## Data Limitations

The historical operating calendar was not available, so days with at least one sale were used as a practical proxy for operating days.

The 2024 data starts partway through the year, so year-over-year comparisons should only be used for comparable periods.

## Confidentiality

This project is based on real business data.

For the public portfolio version, sensitive business information was anonymized or removed. Financial values were adjusted, identifying fields were removed, and some payment methods were grouped into a general category.

## Tools

- Power BI
- Power Query
- DAX
- Excel
- Data Modeling
- Data Cleaning
- Data Visualization

![Executive Overview](executive-overview.jpg)

![Sales Trends and Seasonality](sales-trends-seasonality.jpg)

![Financial Performance](financial-performance.jpg)
