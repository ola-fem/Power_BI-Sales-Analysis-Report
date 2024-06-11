# Sales Dashboard: Data Analysis and Visualization in Power BI

## Introduction
This project involved creating advanced dashboards in Power BI for the fictional manufacturing company AdventureWorks Cycles. The goal of the project was to transform raw data into professional-quality reports and dashboards to track key performance indicators, compare regional performance, analyze product-level trends, and identify valuable customers.

## Project Description
- **Role**: Business Intelligence Analyst
- **Company**: AdventureWorks Cycles (fictional manufacturing company)
- **Scope**:
  - **Connecting and transforming raw data**: Collecting and profiling data from various sources, transforming tables, using tools to edit and merge queries.
  - **Building the data model**: Creating relational data models, establishing relationships between tables, understanding cardinality and filter flow.
  - **Calculating measures using DAX**: Adding calculated columns and measures, writing common formulas and functions in DAX.
  - **Visualizing data with dashboards**: Designing interactive dashboards, inserting charts, customizing formats, editing interactions, applying filters, and using bookmarks.

## Dashboards

### 1. Revenue and Orders Overview
![Revenue and Orders Overview](dashboards\1.png)

The Revenue and Orders Overview Dashboard provides a high-level summary of key business metrics. This dashboard is designed to offer a snapshot of the company's performance in terms of revenue, profit, orders, and return rates. Here are the main components of the dashboard:

**Key Components:**

1. **Company Logo and Name:**
   - **Logo and Name:** Displays the company logo and name, "AdventureWorks," prominently at the top of the dashboard.

2. **Key Performance Indicators (KPIs):**
   - **Revenue:** Shows the total revenue generated.
   - **Profit:** Displays the total profit earned.
   - **Orders:** Indicates the total number of orders placed.
   - **Return Rate:** Shows the percentage of orders that were returned.

3. **Revenue Trending Chart:**
   - **Revenue Trend Line:** A line chart showing the trend in revenue over a specified time period, providing insights into revenue growth or decline.

4. **Orders by Category:**
   - **Category Breakdown:** A bar chart displaying the number of orders by product categories, such as Accessories, Bikes, and Clothing.

5. **Top 10 Products:**
   - **Product List:** A table listing the top 10 products based on orders, revenue, and return percentage. This provides a quick view of the best-performing products and their return rates.

6. **Monthly Metrics:**
   - **Monthly Revenue:** Shows the revenue for the current month and the percentage change from the previous month.
   - **Monthly Orders:** Displays the number of orders for the current month and the percentage change from the previous month.
   - **Monthly Returns:** Indicates the number of returns for the current month and the percentage change from the previous month.

7. **Most Ordered and Most Returned Product Types:**
   - **Most Ordered Product Type:** Highlights the product type with the highest number of orders.
   - **Most Returned Product Type:** Highlights the product type with the highest return rate.

**Interactive Elements:**
- **Date Slider:** Allows users to adjust the date range for the revenue trending chart to focus on specific periods.
- **Filter Options:** Users can apply various filters to the data to customize their view and analyze specific segments.


### 2. Geographical Sales Performance
![Geographical Sales Performance](dashboards\2.png)

The Geographical Sales Performance Dashboard provides an insightful visualization of sales data across different regions. This dashboard is designed to help users understand the geographical distribution of sales and identify key markets. Here are the main components of the dashboard:

**Key Components:**

1. **Regional Tabs:**
   - **Tabs for Continents:** Allows users to switch between different continents (e.g., Europe, North America, Pacific) to view sales performance specific to each region.

2. **World Map Visualization:**
   - **Interactive Map:** Displays a world map with markers indicating sales volumes in various countries.
   - **Country Markers:** The size of the markers represents the sales volume in each country, providing a quick visual reference for high and low-performing regions.

3. **Country Labels:**
   - **Country Names:** Each marker is labeled with the name of the country it represents, ensuring clear identification of sales regions.

**Interactive Elements:**
- **Region Selection:** Users can select different regions by clicking on the tabs, which updates the map to display sales data for the chosen continent.
- **Hover and Click Actions:** Users can hover over or click on the markers to view detailed sales data for specific countries, such as total sales figures and other relevant metrics.


### 3. Product Detail
![Product Detail](dashboards\3.png)


The Product Detail Dashboard provides a comprehensive view of the performance metrics of individual products. This dashboard is crucial for understanding how each product contributes to overall business performance, allowing for strategic adjustments and improvements.

**Key Features:**

1. **Selected Product Overview:**
   - **Selected Product:** Displays the name of the currently selected product for detailed analysis. For instance, "Water Bottle - 30 oz."
   
2. **Monthly Performance Metrics:**
   - **Monthly Orders vs. Target:** Shows the number of orders for the selected product compared to the set target. 
   - **Monthly Revenue vs. Target:** Indicates the revenue generated from the selected product against the target revenue.
   - **Monthly Profit vs. Target:** Displays the profit earned from the selected product in comparison to the target profit.

3. **Price Adjustment Simulation:**
   - **Price Adjustment (%):** Allows users to simulate the impact of price changes on total and adjusted profit. Users can adjust the price percentage to see potential changes in financial outcomes.

4. **Trend Analysis:**
   - **Total Profit and Adjusted Profit Trends:** Line charts showing the trends in total profit and adjusted profit over time for the selected product.
   - **Profit Trend Analysis:** A detailed area chart illustrating profit trends over a specific period. This helps in identifying patterns and seasonality in product performance.

5. **Report Summary:**
   - **Order Summary:** Provides a brief summary of total orders for the selected product.
   - **Profit Trends:** Highlights significant trends in both adjusted and total profit over a defined period.
   - **Performance Insights:** Provides key insights and observations about the product's performance, including periods of highest and lowest profit.

**Interactive Elements:**
- Users can select different metrics such as Orders, Revenue, Profit, Returns, and Return Percentage to view the relevant data trends.
- The date range slider allows users to focus on specific periods to analyze product performance in detail.



### 4. Customer Detail
![Customer Detail](dashboards\4.png)

This dashboard presents a detailed view of customer metrics and performance, specifically focusing on top customers, orders, and revenue. Here is a breakdown of the components included:

**Key Features:**

1. **Overview Metrics**
    - **Unique Customers:** indicating the total count of unique customers.
    - **Revenue per Customer:** representing the average revenue generated per customer.

2. **Graphical Analysis**
    - **Total Customers Over Time:** a line graph showing the trend in the number of total customers over a specified period. This graph includes a timeline slider for adjusting the view range.

3. **Donut Charts**
    - **Orders by Income Level:** a donut chart breaking down the orders by different income levels: High, Average, and Low.
    - **Orders by Occupation:** a donut chart categorizing orders based on occupation groups: Management, Professional, and Skilled Manual.

4. **Top Customers Table**
    - This table lists the top 100 customers sorted by revenue, displaying their customer key, full name, number of orders, and total revenue generated.

5. **Top Customer Highlight**
    - **Top Customer (by Revenue):** a highlighted section showing the name of the top customer based on revenue.
    - **Orders:** number of orders placed by the top customer.
    - **Revenue:** total revenue generated by the top customer.

## Summary
This project is a comprehensive example of data analysis and visualization in Power BI. It allows for tracking key performance indicators, analyzing regional and product performance, and identifying valuable customers, which can support strategic business decision-making.
