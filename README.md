# <div align="center">BMW Car Sales Dashboard</div>

![Intro](https://github.com/PyanshuXd/Power_Bi_FlipkartSales/blob/02038d42c728d3296a71b598d8941b7c0026227b/Images_Used/Intro.jpg)

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

![Objective](https://github.com/PyanshuXd/Power_Bi_FlipkartSales/blob/02038d42c728d3296a71b598d8941b7c0026227b/Images_Used/objective.png)

## Technology Used in the Project:
- Power BI Desktop: For data modeling, visualization, and report creation.
- Microsoft Excel: For storing and managing raw data in three Excel files.
- Power Query: For data transformation and cleaning.
- DAX (Data Analysis Expressions): For creating calculated columns and measures.
- Power BI Service: For publishing and sharing the report online.

## Scope of the Project:
Consolidate data from Excel file: Sales Data
- Create a relational data model to link the tables.
- Develop interactive visualizations to analyze sales trends, Year-wise performance, and Most demanding items.
- Publish the report to Power BI Service for stakeholder access.

![requirement](https://github.com/PyanshuXd/Power_Bi_FlipkartSales/blob/02038d42c728d3296a71b598d8941b7c0026227b/Images_Used/tools.jpeg)

## DAX Queries used and Execution Results:

•	QTD Sales = TOTALQTD(SUM(Flipkart_Data[Price(Dollar)]), 'Calendar'[Date])

•	YTD Product Sold = TOTALYTD(COUNT(Flipkart_Data[Product Category]), 'Calendar'[Date])

•	YTD Reviews = TOTALYTD(SUM(Flipkart_Data[Number of  reviews]), 'Calendar'[Date])

•	YTD Sales = TOTALYTD(SUM(Flipkart_Data[Price(Dollar)]), 'Calendar'[Date])

## Challenges Faced in the Project:
- Data Inconsistency: Some records in the Excel files had missing or inconsistent data, which required cleaning.
- Complex Relationships: Establishing relationships between multiple tables was initially challenging.
- Performance Issues: Large datasets caused slow loading times, which were resolved by optimizing the data model.

## Conclusion:
This Power BI project successfully consolidated and analyzed Flipkart sales data from multiple Excel files, providing actionable insights through interactive visualizations. The dashboard enables stakeholders to make data-driven decisions, improving sales performance and customer satisfaction. With future enhancements, the project can further streamline sales analysis and forecasting.

## Screenshots:
Include screenshots of the Power BI dashboard, data model, and visualizations.

![Page 1](https://github.com/PyanshuXd/Power_Bi_FlipkartSales/blob/02038d42c728d3296a71b598d8941b7c0026227b/Images_Used/Dashboard.png)
