# Superstore Sales Dashboard
created by Anna Dudek @Anna-portfolio

**Nominated for the Top 6 submissions in a global Power BI competition organized by the former employer  (ca. 3k participants in total)**

# _v2 - overview:

## Data Model Overview
- FactOrders - main fact table containing order-level data
- DimCustomer - customer dimension table
- DimProduct — product dimension table
- DimGeography - geographic data
- DimDate - date dimension (calendar table)
- Measures - dedicated table storing DAX measures (best practice)
- staging_orders (hidden) - staging table used for data preparation
<br>

## Data Model Relationships
The model is built on one-to-many relationships:
- DimCustomer[Customer ID] → FactOrders[Customer ID]
- DimProduct[Product ID] → FactOrders[Product ID]
- DimGeography[GeographyID] → FactOrders[GeographyID]
- DimDate[Date] → FactOrders[Order Date]
<br>

## Pages Overview
- Page #1 Cover: dashboard title page
- Page #2 Trends and YoY Change: analysis of trends and year-over-year changes (sales, profit, orders, customers)
- Page #3 Profit Overview: profit analysis by category, region, and state
- Page #4 Orders – Top 5 States: ranking of the top 5 states by total number of orders
<br>


## Good practices applied:
- separate DAX measures table
- clean star schema data model
- clear and consistent naming conventions
- structured multi-page dashboard design
<br>

## Dataset & Resources
- Dataset source: https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting
- Cover image source: https://pixabay.com/pl/photos/biznes-informacja-ksi%C4%99gowo%C4%87-3528035/

This dashboard does not contain any confidential data.
