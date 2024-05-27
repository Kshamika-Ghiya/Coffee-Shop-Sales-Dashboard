# Coffee-Shop-Sales-Dashboard
Analyzed coffee shop sales data to identify trends, patterns, and insights for improving operational efficiency and customer satisfaction.

## Dataset
Dataset encompasses essential details about coffee shop transactions, including transaction specifics, store information, and product details. It provides a robust foundation for conducting comprehensive analyses and deriving actionable insights to enhance operational efficiency and customer satisfaction.

## OBJECTIVES
### OBJECTIVE 1
#### Prepare the data for analysis
The first objective is to explore the coffee shop dataset, conduct some basic data QA and profiling, and add calculated date and time fields to prepare the data for analysis.

Tasks to be done
1. Take a moment to familiarize yourself with the data. How many transactions were recorded, over what period of time? What products and product categories were sold?
2. Add a new column to calculate Revenue (price * quantity)
3. Add new columns to calculate Month and Day of Week based on the transaction date (BONUS: display them as text (ie “Jan”, “Feb”, “Sun”, “Mon”), instead of numerical values)
4. Add a new column to extract Hour from the transaction time

### OBJECTIVE 2
#### Explore the data with Pivot Tables
The second objective is to slice and dice the coffee shop data with Excel PivotTables, and create views to analyze time series and product-level trends.

Tasks to be done
1. Insert a PivotTable on a new tab to show revenue by month
2. Add two more PivotTables (on the same sheet) to show the number of transactions by day of week and by hour of day
3. Add a PivotTable (on the same sheet) to show the number of transactions by product category, sorted descending by transactions
4. Add a PivotTable (on the same sheet) to show the number of transactions and revenue by product type, sorted descending and filtered to the Top 15 (by transactions)


### OBJECTIVE 3
#### Build a dynamic dashboard
The final objective is to visualize the data with Pivot Charts, design an interactive dashboard, and identify insights and recommendations for the coffee shop.

Tasks to be done
1. Add Pivot Charts to show revenue by month as a line chart, transactions by day of week and hour of day as column charts, and transactions by product category as a bar chart
2. Assemble the charts into a rough dashboard layout, and include space for the PivotTable showing Top 15 product types (you can design your own layout, or follow the solution)
3. Add a slicer for store location, and connect it to all of the PivotTables on the sheet
4. Adjust formatting, alignment and polish to finalize the dashboard (TIP: hide the raw PivotTables and remove the worksheet gridlines)
5. Do you notice any interesting patterns or trends? What recommendations might you offer to improve Maven Roasters operations?


## Tasks Accomplished:
- Explored the dataset to understand the number of transactions recorded and the timeframe covered. Also identified the range of products and product categories sold.
- Added a new column to compute revenue by multiplying price and quantity for each transaction.
- Created new columns to extract month, day of the week, and hour from the transaction date and time. Additionally, displayed these values as text (e.g., "Jan", "Feb", "Sun", "Mon") for better readability.

- Created PivotTables to showcase revenue by month, number of transactions by day of week and hour of day, and transactions by product category.
- Developed a PivotTable to exhibit the number of transactions and revenue by product type, filtering the top 15 products by transactions.

- Utilized Pivot Charts to visualize revenue trends by month (line chart), transactions by day of week and hour of day (column charts), and transactions by product category (bar chart).
- Designed an interactive dashboard layout, incorporating space for displaying the top 15 product types.
- Integrated a slicer for store location to allow dynamic filtering across all PivotTables.
- Polished the dashboard layout by adjusting formatting, alignment, and removing gridlines.

## Results
The dynamic dashboard provides comprehensive insights into Maven Roasters' sales data, enabling stakeholders to observe trends, patterns, and key metrics at a glance. Some potential insights and recommendations include identifying peak sales periods, popular product categories, and optimizing staffing schedules to match demand fluctuations. Additionally, analyzing top-selling products can inform inventory management strategies and marketing initiatives to enhance customer satisfaction and drive revenue growth.

## Technologies Used - Microsoft Excel




