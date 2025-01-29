*** Power BI Global Store Dashboard ***

Project Overview  

This project aims to analyze global store sales data and visualize key performance metrics using Power BI. The dashboard provides insights into total sales revenue, sales trends, product performance, and comparisons over time.   


*** Features & Metrics ***  

Total Sales Revenue (KPI visualization)

Sales by Product Category (Pie Chart)

Top Selling Products (Tree Map)

Sales Trend Over Time (Area Chart)

Monthly Sales Comparison (Stacked Column Chart)


*** Dataset ***

The project uses a Global Superstore CSV dataset, which contains sales-related information such as:

Order ID, Customer ID, Product ID

Sales, Profit, Quantity

Order Date, Ship Date, Category, and more


*** Data Preparation & Transformation ***

Data Cleaning: Handled missing values (e.g., filled missing postal codes with "Null").

Custom Columns: Converted date attributes (Order Date, Ship Date) into proper formats.

Data Modeling: Established relationships between tables based on Customer ID, Order ID, and Product ID.


*** Visualization & Design ***

Color Scheme:

White (#FFFFFF), Black (#000000)

Navy Blue (#094780), Blue (#118DFF)

Pink (#E044A7), Orange (#E66C37), Grey (#666666)


*** Font & Styles ***

Headings: Cambria (24)

Visual Titles: Cambria (12)

Labels & Legends: Din (10)

KPI Callout Values: Din (45)


*** Files in This Repository ***

POWER BI dashboard.pbix - dashboard

dashboard_analysis.ipynb – Jupyter Notebook with analysis and insights.

dashboard_script.py – Python script.

dataset/ – Contains the dataset used for visualization.

documentation.pdf – Detailed project documentation.


Sample image:

![image](https://github.com/user-attachments/assets/611b66b0-dfaa-40cd-b506-e051be2c5ab9)
