# <div align="center">BMW Car Sales Dashboard</div>

![Intro](https://github.com/PyanshuXd/Car_Sales-Power-BI-/blob/13a4e20944fd360cdfe9e47826ffb02c6084015c/Images%20Used/dash.png)

## Description:

This project presents an interactive Power BI dashboard for analyzing Flipkart's sales data. The dashboard offers key insights into product performance, customer behavior, sales trends, and regional distribution. It is designed to help stakeholders make data-driven decisions to optimize sales strategies and improve customer engagement.

## Problem Statement:
- Sales, customer, and product data are scattered across multiple sources, making it hard to track performance holistically.
- Manual Excel reports are time-consuming and fail to highlight real-time trends (e.g., top-selling categories, regional demand).
- Difficulty identifying which products, discounts, or regions contribute most to revenue.
- Inability to predict demand spikes or analyze the impact of discounts on sales volume.

## Objectives:
- To consolidate Flipkart sales data from multiple Excel files into a single Power BI dashboard.
- Analyze sales trends across categories, regions, and time periods.
- Identify top-performing products and underperforming segments.
- Provide actionable insights to optimize inventory, marketing, and pricing strategies.

![Objective](https://github.com/PyanshuXd/Car_Sales-Power-BI-/blob/4d21e0d474381dba5af9f3daa155ac409863d1b7/Images%20Used/pngtree-car-salesman-in-dealer-showroom-image_77441.png)

## Technology Used in the Project:
- Power BI Desktop: For data modeling, visualization, and report creation.
- Microsoft Excel: For storing and managing raw data in three Excel files.
- Power Query: For data transformation and cleaning.
- DAX (Data Analysis Expressions): For creating calculated columns and measures.
- Power BI Service: For publishing and sharing the report online.

## Scope of the Project:
Consolidate data from three Excel files: Sales Data, Car Data, and Country Data.
- Create a relational data model to link the tables.
- Develop interactive visualizations to analyze sales trends, country wise performance, and customer demographics.
- Publish the report to Power BI Service for stakeholder access.

![requirement](https://github.com/PyanshuXd/Car_Sales-Power-BI-/blob/c13753c2613c9ed4cbb00d12036099641b054ffb/Images%20Used/Bi%20x%20excel.png)

## DAX Queries used and Execution Results:

•	QTD Sales = TOTALQTD(SUM(Flipkart_Data[Price(Dollar)]), 'Calendar'[Date])

•	YTD Product Sold = TOTALYTD(COUNT(Flipkart_Data[Product Category]), 'Calendar'[Date])

•	YTD Reviews = TOTALYTD(SUM(Flipkart_Data[Number of  reviews]), 'Calendar'[Date])

•	YTD Sales = TOTALYTD(SUM(Flipkart_Data[Price(Dollar)]), 'Calendar'[Date])

