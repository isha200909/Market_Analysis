# Food Distribution Sales Analysis (Power BI)

## Project Overview
This project analyzes 2012-2014 sales performance for a global food distribution company using Power BI. The goal is to convert operational sales data into business-ready insights that support decisions in product strategy, customer management, and regional planning.

The report was built as a four-page Power BI dashboard:
- Dashboard
- Product Details
- Customer Details
- Customer Location

## Problem Statement
The business has multi-year sales records across products, customers, and locations, but lacks a clear decision view for:
- Which products and customers drive the highest sales.
- How sales and margins change over time.
- Which regions and cities contribute most to revenue.
- How quantity and sales relationships vary across products.

Without a consolidated analytical view, teams cannot quickly identify growth opportunities, high-value customers, and regional performance gaps.

## Analytical Approach
The report uses a page-by-page approach to answer core business questions.

### 1) Executive Dashboard
Purpose: Provide a high-level snapshot of performance and key contributors.

Approach:
- Aggregate sales outcomes into top-level visuals.
- Use bar and clustered bar charts to compare top products/customers.
- Use slicers to allow filtering by key dimensions for rapid exploration.

Value:
- Quickly identifies major revenue drivers.
- Supports management-level review before deeper drill-down.

### 2) Product Details
Purpose: Understand product-level performance trends and profitability behavior.

Approach:
- Use trend visuals (line chart) to observe sales movement over time.
- Use combo chart (line + stacked column) to evaluate sales against margin behavior.
- Use treemap to compare contribution concentration across product categories.

Value:
- Highlights strong/weak products over time.
- Supports assortment and margin improvement decisions.

### 3) Customer Details
Purpose: Analyze customer contribution and purchasing behavior.

Approach:
- Use bar visuals and ranked views to identify top customers (including Top 5 analysis).
- Use scatter chart to evaluate relationship patterns between quantity and sales.
- Use tabular/pivot-style view for detailed customer-level comparisons.

Value:
- Identifies high-value customer segments.
- Supports account prioritization and targeted sales actions.

### 4) Customer Location
Purpose: Evaluate geographical sales distribution.

Approach:
- Use map visual to display city-level sales contribution.
- Compare regions using 100% stacked bar to understand proportional performance.

Value:
- Reveals location-based strengths and underperforming regions.
- Supports territory planning and regional strategy.

## Data Sources
Data files used in the project are stored in:
- Cities.xlsx
- Customers.xlsx
- Item master.xlsx
- Sales.xlsx
- Sales rep.csv

## Key Outcome
This Power BI project transforms raw distribution sales data into a structured decision-support report that answers product, customer, and geography-focused business questions through interactive visual analysis.

## How to Use
1. Open Submission/Market_Analysis_Food_Distribution.pbix in Power BI Desktop.
2. Refresh data connections if needed.
3. Use slicers and page navigation to explore insights by product, customer, and location.
4. Review each page in sequence: Dashboard -> Product Details -> Customer Details -> Customer Location.
