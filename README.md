## Project Title
### Coffee Sales Data Cleaning and Dashboard Development*
## Objectives
-Clean and organize the data in the orders table by filling in missing customer and product information.

-Ensure consistent and accurate data for analysis by integrating information from related tables (customers and products).

-Build a cohesive data model in Power Pivot to enable meaningful data insights.

-Create a dashboard that provides insightful visualizations of sales performance and customer segmentation.

## Steps Undertaken
#### Data Cleaning

1.Filled missing values for customer details (customername, email, country, and loyalty card) using the XLOOKUP function, referencing the customers table.

2.Resolved missing product details such as roast type, size, unit price in the orders table using Index Match from the products table.

3.Derived coffee type and roast type names using IF statements for logical value assignment.

#### Data Modeling

1.Loaded cleaned datasets into Power Pivot and established relationships between the orders, customers, and products tables.

2.Created a robust data model to support multi-dimensional analysis.

#### Dashboard Development

1.Built pivot tables for key metrics, including sales trends, customer segmentation, and product performance.

2.Developed an interactive dashboard in Excel with slicers and visual elements to allow users to filter and explore data effectively.

## Results:
#### Top Countries by Sales:

- United States led with $35,638.88 in sales, followed by Ireland and the United Kingdom.
  
#### Customer Performance:

- Identified key customers contributing the highest sales. Example: Don Flintiff with $278.01 in sales.
  
#### Sales Distribution:

- Analysis showed product performance by type (e.g., Arabica, Robusta) and size, highlighting demand trends.
  
#### Profitability Insights:

- Profitability data for different product categories and sizes helped identify the most profitable offerings.
