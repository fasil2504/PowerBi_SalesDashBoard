# PowerBi_SalesDashBoard
Pwer Bi portfolio creations 

Data Source:
Exported the data from Excel : https://docs.google.com/spreadsheets/d/1kmZtwNrw9_M0WtZSqfjK89xXlAYUXTzr/edit?usp=sharing&ouid=108249843804995578592&rtpof=true&sd=true

The dataset contains financial information with the following columns:

Segment: Business segment (e.g., Government, Midmarket).
Country: The country associated with the transaction.
Product: Product type (e.g., Carretera).
Discount Band: Discount range applied to the sale.
Units Sold: Number of units sold.
Manufacturing Price: Cost to manufacture the product.
Sale Price: Price at which the product was sold.
Gross Sales: Total sales before any discounts.
Discounts: Discounts applied.
Sales: Sales after discounts.
COGS (Cost of Goods Sold): Cost of goods sold.
Profit: Profit earned from the sale.
Date: Date of the transaction.
Month Number: The numeric representation of the month.
Month Name: The name of the month.
Year: The year of the transaction.

Tools Used:
Microsoft Power BI: Pre-Processing and Data Visualization

Steps to import data as a folder
Get data -> text/csv -> Folder -> import the file

Perform Data Analysis:
Create Visualizations: Use Power BI's visual tools to create charts like bar charts, pie charts, and line graphs to analyze sales, profit, country-wise performance, etc.
Filter and Slicer: You can use filters and slicers to dynamically filter data by product, country, or time (month/year).

Pre-Processing
Check the data types
Remove duplicates
Remove nulls and blanks
Dashboard

To effectively convey insights using a minimum of 7 visuals in Power BI, here's a structured approach you can follow. These visuals will cover various aspects of the data, from sales trends to product performance, offering a comprehensive analysis of the financial data.


1. Bar Chart: Sales by Country
Purpose: Display total sales by country.
Fields: Use "Country" on the X-axis and "Sales" on the Y-axis.
Insight: This shows which countries contribute the most to overall sales and which markets are underperforming.
2. Line Chart: Sales Over Time
Purpose: Analyze sales trends over the months/years.
Fields: Use "Date" on the X-axis and "Sales" on the Y-axis.
Insight: This will reveal seasonal patterns, spikes, or dips in sales across time.
3. Pie Chart: Product Breakdown
Purpose: Visualize the proportion of sales for each product.
Fields: Use "Product" for the slices and "Sales" for the values.
Insight: This helps identify the best-selling products and compare their share of total sales.
4. Stacked Bar Chart: Sales by Segment and Country
Purpose: Compare the performance of different business segments (e.g., Government, Midmarket) across countries.
Fields: Use "Segment" and "Country" on the X-axis, and "Sales" on the Y-axis.
Insight: This reveals which segments are performing better in specific countries.
5. Clustered Column Chart: Profit vs. Units Sold
Purpose: Display the relationship between profit and units sold across different countries or products.
Fields: Use "Country" on the X-axis, and "Profit" and "Units Sold" as values.
Insight: This helps analyze whether high unit sales necessarily lead to high profits, and identify profitable markets.
6. Table Visual: Detailed Sales and Profit Data
Purpose: Provide a detailed table of sales, discounts, profits, and units sold.
Fields: Include "Country", "Product", "Sales", "Discounts", "Profit", and "Units Sold".
Insight: This table allows for a deep dive into the data for users who want detailed information.
7. MAP Visual: Total Sales By cuntry
Purpose: Provide a high-level overview by contry in sales.
Fields: Use measures for total "Sales".
