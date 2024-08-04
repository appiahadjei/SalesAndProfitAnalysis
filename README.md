# Sales and Profit Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tool](#tool)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preparation](#data-preparation)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

## Project Overview
The goal of this project is to provide a comprehensive analysis of sales performance, product and order metrics, and shipping insights for an e-commerce company. This analysis covers data from 2009 to 2012, aiming to uncover trends, evaluate company performance, and provide actionable insights.

Key performance indicators are explored to understand:

- The overall sales performance and trends over the years.
- Product and order analysis to identify top sellers and peak sales periods.
- Shipping insights, including shipping costs and times.
- Customer segments and their impact on sales.
- The visualizations and reports generated with Tableau offer a clear view of the company's performance and help in making data-driven decisions.

## Data Sources
The primary data source for this analysis is the Sales_and_Profit_Analysis CSV file, which contains detailed sales records. The dataset includes the following columns:

- OrderID: Unique identifier for each order.
- OrderDate: Date when the order was placed.
- OrderPriority: Priority level of the order (e.g., Low, Medium, High).
- OrderQuantity: Number of items ordered.
- Sales: Total sales amount for the order.
- Discount: Discount applied to the order.
- ShipMode: Shipping method used (e.g., Standard, Express).
- Profit: Profit earned from the order.
- UnitPrice: Price per unit of the product.
- ShippingCost: Cost incurred for shipping.
- CustomerName: Name of the customer.
- Province: Province where the customer is located.
- Region: Geographical region of the customer.
- CustomerSegment: Segment to which the customer belongs (e.g., Corporate, Home Office).
- ProductCategory: Category of the product sold.
- ProductSub_Category: Sub-category of the product.
- ProductBaseMargin: Base margin for the product.
- ShipDate: Date when the order was shipped.

## Tool
**Tableau Public**

  - Used for data cleaning, transformation, and visualization. The Tableau report provides interactive dashboards that help in understanding various aspects of the sales data. Download Tableau Public [Here](https://www.tableau.com/products/public/download).

## Exploratory Data Analysis
The exploratory data analysis (EDA) aims to answer the following key questions:

- What are the key performance indicators (KPIs)?
- What is the overall sales trend over the entire period and during specific intervals?
- Which products are top sellers?
- What was the peak month for sales?
- How much did shipping cost over the period, and what was the profit/loss?
- How many orders were placed, and did they contribute to profitability?
- Which customer segments had the highest sales?
- What is the average shipping duration by province and shipping mode?

## Data Preparation
In the initial data processing phase, the following tasks were performed:
### Data Loading
  - Imported the CSV file into Tableau for initial inspection.
### Field Types Correction
  - Ensured that each field had the correct data type (e.g., dates, numeric values).
### Handling Missing Values
  - Addressed any missing or null values in the dataset.
### Data Cleaning
  - Removed duplicates, corrected inconsistencies, and standardized formats.
### Data Formatting
  - Formatted dates and numbers to ensure consistency.

## Data Analysis
Key calculated fields in Tableau include:
```tableau
Average Sales: AVG([Sales])
 - This field calculates the average sales amount.
```


## Results and Findings
#### (i) Shipping Costs
  - Surprisingly, shipping with trucks was more expensive than Express Air and Regular Air over the years.
#### (ii) Profitability
  - The company consistently made profits each year.
#### (iii) Top Grossing Products
  - Office machinery, Tables, Telephone and Communications, Chairs and Chairments, Copiers and Fax, and Storage and Organizations were the top 5 product categories in terms of sales.
#### (iv) Customer Segments
  - Corporate customers generated the highest sales, outperforming Home Office, Consumer, and Small Business segments.
#### (v) Geographical Sales
  - Ontario had the highest sales throughout the period.
#### (vi) Shipping Efficiency
  - High-priority orders were shipped in the least number of days.

*Note: Filters in Tableau can be combined (e.g., year 2011 and Home Office segment) to view specific results.*

## Recommendations
### (i) Optimize Shipping Costs
- Review and possibly renegotiate shipping contracts to lower costs, especially for truck shipments.
### (ii) Focus on Top Products
- Invest more in high-grossing product categories to boost sales further.
### (iii) Leverage Corporate Customers
- Develop targeted marketing strategies to attract more corporate customers.
### (iv) Enhance Shipping Efficiency
- Continue to prioritize high-priority orders to maintain shipping efficiency.
## Limitations
- Data Range: The dataset covers only from 2009 to 2012, which may not reflect current trends or changes in the market.
- Filter Limitations: Combining filters in Tableau may lead to specific queries that do not reflect cumulative results.
