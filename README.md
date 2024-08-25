# Coffee Sales Analysis Excel Project

## Overview
In this project, I performed a deep dive into coffee sales data, cleaning and structuring it to ensure precision and clarity. Using Excel functions like XLOOKUP, INDEX and MATCH, and Pivot Tables, I built an analysis that breaks down sales by customer, product, and country. The project culminates in a dynamic dashboard that visualizes key insights and trends, helping to understand customer behavior and market performance.


## Dashboard Visualizations
![Total Sales Over the Years](https://github.com/pirsarandib/excel-project-coffee-sales-main/blob/main/dashbord.jpg)

The `Dashboard` sheet contains the following visualizations:

### 1. Total Sales Over Time
![Total Sales Over the Years](https://github.com/pirsarandib/excel-project-coffee-sales-main/blob/main/Total_Sales.png)

This chart shows how total sales have evolved over different times, helping to identify growth trends and seasonal patterns.

### 2. Sales by Country
![Customers by Country](https://github.com/pirsarandib/excel-project-coffee-sales-main/blob/main/Sales_by_Countries.png)

This bar chart displays the distribution of customers across different countries, highlighting the regions.
### 3. Top 5 Customers
![Top 5 Customers](https://github.com/pirsarandib/excel-project-coffee-sales-main/blob/main/Top_Five_Customers.png)

This bar chart lists the top 5 customers by total sales, providing insight into the most valuable customers.

## Techniques Used

- **Data Cleaning**: The raw data was thoroughly cleaned to ensure accuracy and consistency. This included removing duplicates, correcting errors, and standardizing formats.
  
- **XLOOKUP**: Used for efficient lookup of data across different sheets, ensuring quick and reliable data retrieval.

- **INDEX and MATCH**: Applied to perform complex lookups and extract data based on multiple criteria, providing flexibility over more traditional lookup functions.

- **Pivot Tables**: Pivot Tables were extensively used to summarize large datasets, allowing for dynamic reporting and analysis of trends across different dimensions such as time, geography, and customer segments.

## Sheets Description

### 1. Total_sales
This sheet contains a pivot table summarizing sales data across different coffee types and years. The table includes yearly and monthly breakdowns for each coffee type, giving an overview of how sales have fluctuated over time.

### 2. Top_Five_Customers
This sheet lists the top five customers by total sales. It provides insights into the most valuable customers, helping to focus marketing and customer retention efforts.

### 3. Sales_By_Contries
Here, sales are broken down by country, showing the total revenue generated from each location. This information is useful for understanding geographical performance and identifying strong or weak markets.

### 4. orders
The `orders` sheet contains detailed records of individual sales transactions. Each record includes the order ID, date, customer ID, product ID, quantity, and whether the customer used a loyalty card.

### 5. customers
This sheet holds customer information, including contact details and loyalty card status. It's useful for customer relationship management (CRM) and segmentation.

### 6. products
Product details are provided in this sheet, including coffee type, roast type, size, unit price, and profitability metrics. This helps in analyzing product performance and making inventory decisions.

## How to Use
1. **Exploring Data**: Start by reviewing the `Total_sales` and `Sales_By_Contries` sheets to get a high-level understanding of sales trends.
2. **Customer Insights**: Use the `Top_Five_Customers` and `customers` sheets to dive into customer behavior and demographics.
3. **Order Analysis**: The `orders` sheet provides granular details that can be filtered to analyze specific periods, customers, or products.
4. **Product Performance**: Check the `products` sheet to assess which coffee types and sizes are performing well in terms of sales and profitability.

## Contributing
If you have suggestions or improvements, feel free to create an issue or submit a pull request. Contributions are welcome!

## License
This project is open-source and available under the MIT License.
