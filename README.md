# Retail Sales Analysis Dashboard

## Project Overview

This project analyses retail sales data to identify sales trends,
top-performing products, customer purchasing patterns, store
performance, returns, and inventory risks. The goal is to turn raw
business data into useful insights that can support better business
decisions.

The project was completed using **Microsoft Excel**, with data
preparation, lookup formulas, PivotTables, charts, and an executive
dashboard.

## Business Objectives

-   Measure overall sales performance using key performance indicators
    (KPIs).
-   Identify the best-performing products, categories, stores, regions,
    and months.
-   Understand customer revenue contributions.
-   Review product returns and identify potential return patterns.
-   Highlight inventory risks that may lead to stock shortages.
-   Present findings and recommendations in a clear dashboard and
    summary report.

## Tools and Skills

-   **Microsoft Excel**
-   Data cleaning and preparation
-   Data lookup and joining related tables using lookup formulas
-   Calculated fields and KPI formulas
-   PivotTables and PivotCharts
-   Dashboard design and data visualisation
-   Exploratory data analysis
-   Business reporting and insight communication

## Dataset

The workbook uses related retail data tables, including:

-   **Orders:** order dates, customers, products, stores, quantities,
    prices, discounts, shipping costs, payment methods, sales channels,
    and order status.
-   **Customers:** customer details, demographics, location,
    registration date, and customer segment.
-   **Products:** product names, categories, sub-categories, brands,
    cost prices, and selling prices.
-   **Stores:** store names, regions, states, cities, and opening dates.
-   **Inventory:** stock on hand, reorder levels, and last restock
    dates.
-   **Returns:** return dates, reasons, and refund amounts.
-   **Suppliers:** supplier contact and location details.

## Process

1.  **Prepare the data**\
    Reviewed the available tables and prepared data for analysis.

2.  **Enrich the analysis dataset**\
    Used Excel lookup formulas to bring relevant fields together,
    including store names, states, product categories, brands, customer
    gender, customer segment, product names, and customer names.

3.  **Calculate sales and inventory metrics**\
    Calculated total revenue and inventory value to support KPI
    reporting.

4.  **Build PivotTables**\
    Summarised sales by month, store, category, brand, state, customer
    gender, and customer segment. Also analysed top and bottom products
    and top customers by revenue.

5.  **Create visualisations**\
    Developed charts to show monthly sales trends, revenue by category
    and store, top products, sales by region, and return rate by
    category.

6.  **Build an executive dashboard**\
    Brought key metrics and charts together to provide an at-a-glance
    view of business performance.

7.  **Interpret the findings**\
    Used the results to identify business strengths, risks, and
    opportunities, then prepared recommendations.

## Dashboard KPIs

The dashboard includes the following metrics:

-   Total Revenue
-   Total Orders
-   Total Customers
-   Average Order Value
-   Return Rate
-   Inventory Value

## Key Business Questions

The analysis explores questions such as:

-   Which product generated the highest revenue?
-   Which store and region performed best?
-   Which product category generated the most revenue?
-   Which month had the highest sales?
-   Which customers contributed the most revenue?
-   Which products or categories have high return rates?
-   Which supplier provides the largest number of products?
-   Which stores may need inventory replenishment?
-   What actions could improve sales and inventory management?

## Key Findings

The analysis identified the following results from the workbook:

-   **Top-revenue product:** Beauty Item 228
-   **Top-performing category:** Beauty
-   **Top-performing store:** ShopSmart Lagos
-   **Top-performing region:** Lagos
-   **Highest-revenue month:** December
-   **Stores flagged for low inventory:** ShopSmart Lagos and ShopSmart
    Abuja
-   **Supplier with the highest number of products:** Brown

The top customers by revenue included Ashley Smith, Jennifer Smith,
Jeremy Estes, Jessica Rodriguez, Joseph Smith, Mark Smith, Mary Lee,
Michael Smith, Nicole Smith, and William Rogers.

These findings are specific to the dataset used in this project and
should not be interpreted as results for the retail industry as a whole.

## Recommendations

-   **Prioritise the Beauty category:** Review demand and consider
    targeted promotions or a broader selection of high-performing
    products.
-   **Monitor stock levels:** Review inventory at ShopSmart Lagos and
    ShopSmart Abuja and replenish products approaching their reorder
    levels.
-   **Plan for seasonal demand:** Use December's sales performance to
    inform future stock planning and promotional calendars.
-   **Strengthen customer retention:** Consider suitable loyalty or
    retention activities for high-revenue customers.
-   **Continue monitoring returns:** Use return reasons and
    category-level return rates to identify products that may need
    further investigation.

## Project Deliverables

The project workbook contains:

-   Prepared analysis data
-   Lookup activity
-   PivotTables
-   Sales and return analysis charts
-   Executive dashboard with KPIs
-   Business findings and recommendations

## Limitations and Notes

-   The results depend on the quality and completeness of the supplied
    dataset.
-   Customer segment is used as the available field for membership-level
    analysis.
-   Supplier analysis depends on the relationships available in the
    workbook. If product-to-supplier relationships are not directly
    provided, supplier-level conclusions should be checked against the
    source data.
-   Return-rate conclusions should be validated against the Returns and
    Orders tables before making product-specific decisions.
-   Revenue calculations in this workbook include the order's shipping
    cost after applying the discount to the product subtotal. This
    definition should be confirmed if the business uses a different
    revenue policy.

## What I Learned

Through this project, I practised preparing and analysing related
datasets, using Excel lookup formulas, creating PivotTables and charts,
calculating KPIs, designing a dashboard, and translating findings into
practical business recommendations.

## Future Improvements

-   Add interactive slicers and a timeline for filtering the dashboard.
-   Validate data quality and relationships across all source tables.
-   Improve the return-rate analysis by linking returned orders to their
    products and categories.
-   Rebuild the dashboard in Power BI as a next step.
-   Explore SQL for querying and analysing the underlying data.

------------------------------------------------------------------------

*This project was completed as part of my data analysis learning
journey.*
