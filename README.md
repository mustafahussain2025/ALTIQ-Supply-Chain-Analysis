# ALTIQ Supply Chain  Analysis Using Power BI
# Problem Statement
The ALTIQ Supply Chain Analysis aims to optimize the company's supply chain operations by leveraging the capabilities of Power BI. The analysis focuses on understanding the dynamics between customer orders, product inventory, and fulfillment targets. By integrating and analyzing multiple datasets such as order details, customer information, product data, and date dimensions, the goal is to identify trends, inefficiencies, and opportunities for improvement. The primary objective is to create an interactive dashboard that provides actionable insights to enhance decision-making processes related to supply chain management.

# Approach
Data Import and Preparation:

Data Sources: Import the following datasets into Power BI:
dim_targets_orders: Contains target order metrics.
fact_order_lines: Detailed line items of orders.
fact_orders_aggregate: Aggregated order data.
dim_customers: Customer information.
dim_date: Date-related data.
dim_products: Product information.
Data Cleaning: Ensure data integrity by cleaning and transforming the datasets to handle missing values, ensure consistent data types, and address any discrepancies.
Data Transformation and Modeling:

Data Relationships: Establish relationships between tables to enable comprehensive analysis. Key relationships include:
fact_order_lines to dim_products (Product ID)
fact_order_lines to dim_customers (Customer ID)
fact_order_lines to dim_date (Date)
fact_orders_aggregate to dim_date (Date)
dim_targets_orders to dim_date (Date)
Calculated Columns and Measures: Create calculated columns and measures to derive additional insights, such as total sales, average order value, and order fulfillment rates.
Visualization Creation:
# DASHBOARD LINK : https://app.powerbi.com/groups/me/reports/5de69edb-74e5-4cbd-8267-c570d65758de/ReportSection?experience=power-bi

Order Fulfillment Analysis: Use bar charts and line graphs to visualize order fulfillment rates against targets. Compare actual performance with targets set in dim_targets_orders.
Customer Insights: Develop visuals to analyze customer behavior, such as order frequency, average order value, and top customers by sales volume.
Product Performance: Create visuals to evaluate product performance, including sales trends, inventory levels, and top-selling products.
Time-Series Analysis: Utilize line charts to track orders and sales over time, leveraging the dim_date table to analyze trends by day, month, quarter, and year.
Interactive Dashboard:

Filters and Slicers: Implement interactive filters and slicers to allow users to explore the data by different dimensions, such as date range, customer segment, product category, and geographic region.
Drill-Through Capabilities: Enable drill-through features to provide detailed views of specific data points, such as drilling from an aggregated sales view to individual order details.
KPI Indicators: Incorporate key performance indicators (KPIs) to highlight critical metrics such as order accuracy, delivery time, and customer satisfaction.
Insights and Reporting:

Generate comprehensive reports that provide a holistic view of the supply chain operations. These reports should be designed to be user-friendly and insightful, providing clear and actionable recommendations.
# Conclusion
The ALTIQ Supply Chain Analysis using Power BI provides a robust framework for monitoring and optimizing supply chain activities. Key outcomes include:

Enhanced Visibility: The interactive dashboard offers a clear and comprehensive view of the entire supply chain, from order intake to fulfillment.
Performance Tracking: Users can track performance against targets, identify areas where the supply chain is underperforming, and take corrective actions.
Customer and Product Insights: Detailed insights into customer behavior and product performance help in making informed decisions regarding inventory management, marketing strategies, and customer engagement.
Operational Efficiency: By identifying trends and inefficiencies, the analysis supports efforts to streamline operations, reduce costs, and improve overall supply chain efficiency.
Overall, the Power BI dashboard empowers stakeholders with the data-driven insights needed to enhance the supply chain management process, ensuring that ALTIQ can meet its operational goals and deliver superior value to its customers.
