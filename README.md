# Online Retail Data Analysis | Tableau

## Project Overview

This project focuses on analysing online retail sales data using Tableau. The objective is to explore sales performance, identify top-performing countries and customers, and understand geographical product demand through data visualization.

The project contains four analytical worksheets covering revenue trends, country-wise revenue, customer-wise revenue and geographical quantity distribution.

## Tools & Technologies

- Tableau Desktop
- Data Visualization
- Data Analysis
- Calculated Fields
- Filters and Aggregations

## Dataset Description

The project uses an Online Retail dataset containing the following fields:

- InvoiceNo – Invoice number
- StockCode – Product code
- Description – Product description
- Quantity – Number of products purchased
- InvoiceDate – Transaction date
- UnitPrice – Price per unit
- CustomerID – Customer identification number
- Country – Customer's country

## Analysis Performed

### 1. Monthly Revenue Analysis (Q1)

- Analysed monthly revenue for the year 2011.
- Calculated revenue using quantity multiplied by unit price.
- Applied filters to include only positive quantities and positive unit prices.
- Examined monthly revenue trends.

### 2. Top 10 Countries by Revenue (Q2)

- Analysed revenue across different countries.
- Calculated total revenue for each country.
- Identified the top 10 countries based on revenue.
- Compared country-wise sales performance.

### 3. Top 10 Customers by Revenue (Q3)

- Analysed customer-wise revenue.
- Identified the top 10 customers based on total revenue.
- Excluded records with missing Customer IDs.
- Compared customer contributions to total revenue.

### 4. Geographical Quantity Analysis (Q4)

- Analysed product quantities across different countries.
- Used geographical visualization to represent country-wise quantity distribution.
- Explored the geographical distribution of retail demand.

## Calculated Fields

**1. Revenue**

```text
[Quantity] * [UnitPrice]
```

Calculates revenue for each transaction record.

**2. Valid Quantity**

```text
[Quantity] > 0
```

Identifies records with positive quantities.

**3. Valid Unit Price**

```text
[UnitPrice] > 0
```

Identifies records with positive unit prices.

## Key Objectives

- Understand monthly revenue trends.
- Identify high-revenue countries.
- Recognize top revenue-generating customers.
- Explore geographical sales distribution.
- Practise data analysis and visualization using Tableau.

## How to View the Project

1. Download the `OnlineRetailAnalysis.twbx` file.
2. Open Tableau Desktop.
3. Open the downloaded `.twbx` workbook.
4. Explore the four worksheets (Q1, Q2, Q3 and Q4).

## Skills Demonstrated

- Data Analysis
- Data Visualization
- Tableau
- Calculated Fields
- Data Filtering
- Revenue Analysis
- Customer Analysis
- Geographical Analysis

## Project File

`OnlineRetailAnalysis.twbx` – Tableau Packaged Workbook.
