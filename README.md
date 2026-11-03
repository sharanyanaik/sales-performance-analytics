# Sales Performance Analytics

## 1. Project Overview

The Sales Performance Analytics project analyzes sales data to understand revenue performance, product-line performance, customer purchasing activity, country-wise sales, and monthly sales patterns.

The goal is to turn raw sales records into meaningful insights using SQL and Power BI.

## 2. Objectives

- Calculate key sales performance indicators.
- Identify the product lines generating the highest revenue.
- Compare sales across countries.
- Analyze monthly sales patterns.
- Identify top customers and products.
- Understand the contribution of different deal sizes.
- Present findings in an interactive Power BI dashboard.

## 3. Tools and Technologies

- **MySQL Workbench:** Data querying and analysis using SQL.
- **Microsoft Power BI:** Dashboard creation and data visualization.
- **CSV:** Source data format.

## 4. Dataset

The dataset contains sales order records, including order dates, quantities, sales amounts, product lines, product codes, customer names, countries, and deal sizes.

Important columns include `ORDERDATE`, `SALES`, `QUANTITYORDERED`, `ORDERNUMBER`, `PRODUCTLINE`, `PRODUCTCODE`, `CUSTOMERNAME`, `COUNTRY`, and `DEALSIZE`.

## 5. SQL Analysis

SQL was used to:
- Calculate total sales, quantity sold, distinct orders, and distinct customers.
- Rank product lines by sales revenue.
- Analyze sales by month and country.
- Identify the top 10 customers and products by sales.
- Compare sales across deal-size categories.

The queries are stored in `sales_analysis_queries.sql`.

## 6. Power BI Dashboard

The dashboard includes:
- KPI cards for sales, quantity sold, orders, and customers.
- A bar chart showing sales by product line.
- A bar chart showing sales by country.
- A line chart showing the monthly sales trend.
- A donut chart showing sales by deal size.

**Dashboard screenshot:** Add your final Power BI screenshot to this section.

## 7. Initial Business Insights

- Classic Cars is the highest-performing product line in the current dashboard.
- The USA has the highest sales among the countries displayed.
- Medium deals contribute the largest share of sales in the current donut chart, at approximately 60.68%.
- Deal-size analysis can help the business understand which categories contribute most to revenue.

These findings should be rechecked against the final query results before publication.

## 8. Conclusion

This project demonstrates the use of SQL for data analysis and Power BI for presenting sales information visually. The dashboard helps users compare sales performance across product lines, countries, months, customers, and deal sizes.

## 9. Future Improvements

- Correct and validate the date sorting in the monthly trend.
- Add interactive filters where useful.
- Improve data validation and documentation.
- Add profit analysis if reliable cost data becomes available.
