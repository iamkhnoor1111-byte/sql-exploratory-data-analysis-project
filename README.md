# sql-exploratory-data-analysis-project
Data Warehouse Analytics Project
Overview

This project includes a set of SQL scripts used to build and analyze a data warehouse.
Each file has a specific purpose, starting from creating the database to exploring data and generating reports.

1. Initialization

00_init_database.sql
This file creates the main database called DataWarehouseAnalytics and the schema gold.
If the database already exists, it will be deleted and recreated.
Be careful before running this file because all data in the existing database will be removed.

2. Exploration Scripts

01_database_exploration.sql
Used to check the database structure, tables, and relationships.

02_dimensions_exploration.sql
Used to explore dimension tables such as customers, products, and dates.

03_date_range_exploration.sql
Used to find available date ranges and time periods in the data.

04_measures_exploration.sql
Used to look at main business measures like sales amount, quantity, and revenue.

3. Analysis Scripts

05_magnitude_analysis.sql
Analyzes total sales, revenue, or profit.

06_ranking_analysis.sql
Finds top customers, products, or categories based on performance.

07_change_over_time_analysis.sql
Shows how metrics change over time, like month-over-month or year-over-year.

08_cumulative_analysis.sql
Calculates running or cumulative totals.

09_performance_analysis.sql
Checks performance based on KPIs or targets.

10_data_segmentation.sql
Divides data into groups such as region, category, or customer type.

11_part_to_whole_analysis.sql
Shows how each part contributes to the overall total (for example, percentage of total sales).

4. Reporting Scripts

12_report_customers.sql
Generates a summary report about customers.

13_report_products.sql
Generates a report about product performance and sales.

How to Run

Open SQL Server Management Studio (SSMS) or Azure Data Studio.

Run the scripts one by one in order, starting from 00_init_database.sql and ending with 13_report_products.sql.

Make sure the database is created before running any analysis or report files.
