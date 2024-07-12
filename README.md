# Sales Analysis Dashboard

This Tableau project visualizes key sales metrics to provide comprehensive insights into revenue trends, top-performing countries and customers, and geographic sales distribution.

## Dashboard Overview

The Sales Analysis Dashboard is designed to help you understand and analyze various aspects of sales performance through the following visualizations:

## Visualizations

1. **Monthly Revenue 2011**:
   - **Type**: Line Chart
   - **Description**: Displays the total revenue generated each month for the year 2011. This helps in understanding the monthly revenue trends and identifying peak sales periods.
   - **Fields Used**: `Invoice Date`, `Revenue` (calculated as `[Quantity] * [Unit Price]`)

2. **Top 10 Countries by Revenue (excluding UK)**:
   - **Type**: Side-by-Side Bar Chart
   - **Description**: Shows the top 10 countries by total revenue and quantity sold, excluding the United Kingdom. This highlights the most profitable international markets and the volume of products sold in those regions.
   - **Fields Used**: `Country`, `Revenue`, `Quantity`
   - **Filters**: Exclude `United Kingdom`

3. **Top 10 Customers by Revenue**:
   - **Type**: Column Chart
   - **Description**: Identifies the top 10 customers based on the total revenue they generated. This helps in recognizing key customers who contribute significantly to the sales.
   - **Fields Used**: `CustomerID`, `Revenue`
   - **Filters**: Top 10 by `Revenue`

4. **Units Sold by Country (excluding UK)**:
   - **Type**: Map Chart
   - **Description**: Illustrates the total units sold in each country, excluding the United Kingdom. This provides a geographic view of product distribution and sales concentration.
   - **Fields Used**: `Country`, `Units Sold` (calculated as `[Quantity]`)
   - **Filters**: Exclude `United Kingdom`
