Blinkit Real-Time Sales Dashboard Analysis Using Power BI

Project Title:
Real-Time Blinkit Sales Performance & Insights Dashboard-

Objective:
To conduct a comprehensive analysis of Blinkit’s sales performance, customer satisfaction, and inventory distribution. This is achieved by identifying key KPIs and creating interactive dashboards using Power BI, enabling stakeholders to monitor and make data-driven decisions.
Project Workflow:

1. Requirement Gathering / Business Understanding
Understood Blinkit's business goals related to sales, customer ratings, and inventory distribution.
Identified performance metrics and visualization needs.

2. Data Walkthrough
Explored the structure and nature of the dataset (products, ratings, sales, outlet info).
Identified key columns like item type, fat content, sales amount, rating, outlet location.

3. Data Connection
Connected the real-time / historical dataset to Power BI using appropriate connectors.

4. Data Cleaning & Quality Check
Removed duplicates, handled null values.
Standardized category names like “Low Fat”, “Regular”, “High Fat” for consistency.
Verified data accuracy for metrics like sales and ratings.

5. Data Modeling
Created data relationships between different tables (e.g., Items, Outlets, Sales).
Established star schema for optimal performance and analysis.

6. Data Processing
Transformed raw data using Power Query.
Created calculated columns for required insights.

7. DAX Calculations
Defined key measures such as:
Total Sales = SUM(SalesAmount)
Average Sales = AVERAGE(SalesAmount)
Number of Items = COUNT(ItemID)
Average Rating = AVERAGE(Rating)

8. Dashboard Layouting
Planned an intuitive layout separating KPIs, charts, and filters.
Used bookmarks and slicers for interactive experience.

9. Chart Development & Formatting
Selected visualizations based on insight goals (detailed below).
Customized formatting, tooltips, and color themes for clarity.

10. Dashboard / Report Development
Developed multiple dashboards combining KPIs, charts, filters, and geo visuals.
Ensured mobile responsiveness and optimized for performance.

11. Insights Generation
Generated actionable insights from each visualization.
 Business Requirement Overview:
To analyze Blinkit's performance using key metrics and visual tools in Power BI. The aim was to uncover patterns in customer behavior, product performance, and outlet efficiency using the following KPIs:

KPI Metrics Tracked:
1. Total Sales – Total revenue from all items sold.
2. Average Sales – Revenue per sale on average.
3. Number of Items – Total number of distinct items sold.
4. Average Rating – Mean customer satisfaction rating.

Key Insights (Examples):
Outlets with "Low Fat" items had higher average sales.
Supermarkets and Medium-sized outlets contributed the most to overall sales.
Older outlets performed better in customer ratings.
Urban outlet locations yielded more revenue than rural areas.
Chart Requirements and Visual Objectives (in Points):
•	Total Sales by Fat Content
o	Objective: Analyze how fat content impacts total sales.
o	Chart Type: Donut Chart
o	Metrics Included: Total Sales, Average Sales, Number of Items, Average Rating
•	Total Sales by Item Type
o	Objective: Compare sales performance across different item categories.
o	Chart Type: Bar Chart
o	Metrics Included: Total Sales, Average Sales, Number of Items, Average Rating
•	Fat Content by Outlet for Total Sales
o	Objective: Evaluate how fat content performs across various outlets.
o	Chart Type: Stacked Column Chart
o	Metrics Included: Total Sales, Average Sales, Number of Items, Average Rating
•	Total Sales by Outlet Establishment Type
o	Objective: Analyze the influence of outlet age or type on sales.
o	Chart Type: Line Chart
o	Metrics Included: Total Sales
•	Sales by Outlet Size
o	Objective: Explore the relationship between outlet size and total revenue.
o	Chart Type: Pie/Donut Chart
o	Metrics Included: Total Sales
•	Sales by Outlet Location
o	Objective: Provide a geographical comparison of sales across locations.
o	Chart Type: Funnel Map
o	Metrics Included: Total Sales
•	All KPIs by Outlet Type
o	Objective: Deliver a detailed overview of all key metrics by outlet type.
o	Chart Type: Matrix Card
o	Metrics Included: Total Sales, Average Sales, Number of Items, Average Rating



Tools & Technologies Used:
•	Power BI (Data Modeling, DAX, Visualization)
•	Microsoft Excel (Initial data cleaning)
•	Power Query (ETL Process)

Challenges Faced:
•	Missing values in customer ratings required handling with median imputation.
•	Standardizing multiple inconsistent fat content labels.
•	Real-time refresh of data needed scheduled Power BI refresh setup.

Future Enhancements:
•	Integrate real-time API for live sales tracking.
•	Include customer demographics for segmentation analysis.
•	Add forecasting models to predict future sales trends.
•	Enable drill-through reports for outlet-level management.

Conclusion:
This Blinkit Dashboard project provided a powerful visual overview of sales and customer behavior across outlets. It helped derive meaningful insights that can be used for inventory planning, marketing strategies, and customer satisfaction improvement. Power BI enabled the creation of an interactive, scalable, and visually engaging reporting solution for real-time decision-

