# Coffee Sales Analysis Dashboard | Microsoft Excel

## Project Overview

This project analyses coffee sales data using Microsoft Excel to identify sales trends, customer purchasing patterns, product performance, and geographic performance.

The project demonstrates an end-to-end Excel analytics workflow, including data preparation, lookup functions, PivotTables, PivotCharts, filtering, and interactive dashboard development.

## Project Objectives

The analysis was designed to answer key business questions including:

* How have coffee sales changed over time?
* Which coffee types generate the most sales?
* Which countries contribute the most revenue?
* Who are the highest-value customers?
* How do roast type, coffee size, and loyalty status affect sales?
* How can sales performance be presented in an interactive dashboard for decision-making?

## Dashboard Preview

![Coffee Sales Dashboard](images/coffee-sales-dashboard.png)

## Dataset

The workbook contains three primary source tables:

* **Orders** – individual customer orders and quantities
* **Customers** – customer information, location, and loyalty status
* **Products** – coffee type, roast type, size, unit price, and profit information

The project contains approximately **1,000 order records**.

> The dataset is used for portfolio and educational analysis.

## Data Preparation

The original order data was enriched by combining information from the customer and product tables.

Excel functions used during the preparation process included:

* `XLOOKUP`
* `INDEX`
* `MATCH`
* `IF`

These functions were used to retrieve customer and product attributes and create a consolidated analytical dataset.

The resulting **Clean orders** table contains information including:

* Order ID
* Order Date
* Customer ID
* Product ID
* Quantity
* Customer Name
* Email
* Country
* Coffee Type
* Roast Type
* Size
* Unit Price
* Sales

## Analysis

PivotTables were created to investigate several areas of business performance.

### Sales Over Time

Monthly and yearly sales were analysed for the four coffee varieties:

* Arabica
* Excelsa
* Liberica
* Robusta

This allows sales patterns and changes in product demand to be compared over time.

### Sales by Country

Sales were analysed across:

* United States
* Ireland
* United Kingdom

The United States generated the largest share of sales in the dataset.

Total analysed sales were approximately **£45.1K**.

### Top Customers

Customer-level sales were aggregated to identify the highest-value customers.

This analysis helps demonstrate how transactional data can be used for customer segmentation and retention-focused decision-making.

## Dashboard

An interactive Excel dashboard was developed to bring the main analyses together in one reporting interface.

The dashboard includes:

* Sales trends over time
* Sales by country
* Top customers
* Coffee-type analysis
* Interactive filters and slicers

The dashboard allows users to explore the data without working directly with the underlying tables.

## Excel Skills Demonstrated

This project demonstrates practical use of:

* Data cleaning
* Data preparation
* Excel Tables
* XLOOKUP
* INDEX and MATCH
* IF statements
* PivotTables
* PivotCharts
* Sorting and filtering
* Slicers
* Sales analysis
* Customer analysis
* Dashboard design
* Business data visualisation

## Workbook Structure

| Worksheet         | Purpose                            |
| ----------------- | ---------------------------------- |
| orders            | Original order-level data          |
| customers         | Customer reference data            |
| products          | Product and pricing information    |
| Clean orders      | Prepared dataset used for analysis |
| Documentation     | Project documentation              |
| Total Sales       | Sales trend PivotTable             |
| Country Bar Chart | Country-level sales analysis       |
| Top 5 Customers   | Highest-value customer analysis    |
| Dashboard         | Final interactive Excel dashboard  |

## Key Learning

This project strengthened my ability to take data stored across multiple tables, combine and prepare it for analysis, investigate business questions using PivotTables, and communicate findings through an interactive Excel dashboard.

It forms part of my practical data analytics portfolio and demonstrates how Microsoft Excel can be used to transform raw transactional data into useful business insights.

## Tools

**Microsoft Excel**

Key features used:

`XLOOKUP` | `INDEX-MATCH` | `PivotTables` | `PivotCharts` | `Slicers` | `Excel Tables` | `Dashboarding`

## Author

**Aisosa Elizabeth Erhunmwunsee**

Data Analytics Portfolio
