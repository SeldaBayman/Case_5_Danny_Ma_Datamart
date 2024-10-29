# Case_5_Danny_Ma_Datamart

![Case_5](https://github.com/user-attachments/assets/df41ad18-6243-4335-8f00-9fa31fde8ebf)

Datamart SQL Data Analysis
📝 Case Study #5: Data Cleansing and Exploration for Data Mart
Welcome to the fifth case study from Danny Ma's SQL Challenge! This project tackles data cleansing and exploratory analysis on weekly sales data, addressing data quality issues and deriving key insights across demographics, platforms, regions, and more.

![schema](https://github.com/user-attachments/assets/7dcaa938-3a46-43f4-bd87-33d1fda5ba5f)

📑 Table of Contents
Project Overview
Data Cleansing and Transformation
Exploratory Analysis
Before & After Analysis
Insights and Recommendations
SQL Queries

![1_1](https://github.com/user-attachments/assets/94c907bd-9050-4d0d-8757-e31c599162cf)
![1_2](https://github.com/user-attachments/assets/f2aa473b-76a5-4b40-9a95-38f001fab580)
![1_3](https://github.com/user-attachments/assets/d6b4fac4-81c4-452e-8124-e4765c7093b2)
![1_4](https://github.com/user-attachments/assets/d5eb5306-9825-48fc-b88b-2f4a1c9e331d)

![2 2](https://github.com/user-attachments/assets/d8616054-873c-4d37-bd17-96b1c01109d7)

![2 3](https://github.com/user-attachments/assets/ca5da016-dfdc-48c4-ad48-74240750bb39)

![2 8](https://github.com/user-attachments/assets/b01657cf-603f-45bb-9979-9bd0cf1d7dd2)

![4_1](https://github.com/user-attachments/assets/924316b5-c326-44e3-9caa-596f94513634)

Conclusion

1. Project Overview
In this case study, we perform essential data cleansing and transformations to prepare for analysis on weekly sales data for Data Mart. The project focuses on refining date formats, categorizing demographics, and calculating meaningful metrics like avg_transaction, which we will use in deeper analysis to answer specific business questions. The goal is to:

Address missing values and ensure data consistency.
Transform segment data to provide meaningful age and demographic insights.
Calculate yearly, monthly, and weekly metrics and analyze changes over time.
2. Data Cleansing and Transformation
We begin by creating a clean, transformed version of the dataset in the data_mart schema with a new table called clean_weekly_sales. Key transformations include:

Date and Calendar Transformations: Converting the week_date field into a date format and creating columns for week_number, month_number, and calendar_year.
Demographic and Age Band Mapping: Assigning each segment to an age band (e.g., Young Adults, Middle-Aged, Retirees) and demographic group (Couples, Families).
Handling Null Values: Replacing all null values with "unknown" in relevant columns.
Additional Metrics: Creating an avg_transaction column as sales / transactions, rounded to two decimal places.

3. Exploratory Analysis
Once the data is cleansed, we dive into a series of exploratory queries to answer specific questions:

Weekday Patterns: Analyzing which days of the week are represented for week_date values.
Missing Week Numbers: Identifying any missing weekly data and understanding its impact.
Annual and Monthly Transactions: Summing up total transactions per year and sales per region and month.
Platform Comparison: Calculating the percentage split of sales between Retail and Shopify by month.
Demographic and Age Band Analysis: Analyzing the contribution of each demographic and age band to Retail sales.

4. Before & After Analysis
This section explores the impact of sustainable packaging changes introduced in mid-2020. The analysis compares sales before and after June 15, 2020 to measure performance across demographics, age groups, platforms, and regions.

Key Metrics:
Sales for 4 and 12 Weeks Before and After the Change: Summing total sales and calculating growth rates.
Historical Comparison with 2018-2019 Data: Observing differences in sales metrics to understand year-over-year changes.

5. Insights and Recommendations
Based on the data analysis, here are some notable insights:

Platform Trends: Retail significantly outperformed Shopify in certain months, possibly due to increased foot traffic or marketing efforts.
Demographic Insights: Families contributed the most to overall sales, with the Retirees age band showing strong engagement on the Retail platform.
Impact of Sustainable Packaging: The introduction of sustainable packaging appears to correlate with an increase in sales, suggesting positive customer response.
Recommendations:

Targeted Campaigns: Focus on Families and Retirees for Retail campaigns, as they show strong engagement in physical stores.
Shopify Optimization: Increase efforts on Shopify to close the performance gap with Retail.
Sustainability Marketing: Highlight sustainable initiatives in promotions, as the positive response from the packaging change indicates customer interest.
6. SQL Queries
All SQL queries used in this project are provided in a sequential order for each section of the analysis:

Data Cleansing Queries
Exploratory Analysis Queries
Before & After Analysis Queries
These queries can be found in the queries.sql file in the repository.

7. Conclusion
This case study highlights the importance of data cleansing in achieving reliable insights, especially when analyzing customer segments and sales performance over time. By transforming and enriching the data, we could reveal trends and make data-driven recommendations to enhance Data Mart’s business strategies.

Thank you for exploring this case study! 😊

