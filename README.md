# Infonative-Task-for-reporting-Effort-Data-
Hi, This is a reporting based project/assignment given to me by Infonative Solutions for a Data Analyst role for Delloitte and Assignment was purely based to assess the Excel skills. Kindly find the details in repository items. If you want to try out it yourself, kindly find the question template and Raw Data attached and you can do it hands on. All the best :) 
1. Project Overview
This project provides a robust solution for automating the analysis and reporting of a Quality Assurance (QA) team's effort data. It transforms three separate raw data files (weekly efforts, resource details, and a fiscal calendar) into a single, interactive dashboard within Microsoft Excel.

The solution leverages Excel's powerful data tools, Power Query and Power Pivot, to create a fully refreshable report, eliminating the need for manual data cleaning and repetitive calculations.

2. Key Reports & Features
The final Excel dashboard provides two main analytical views with interactive filtering capabilities:

Report 1: Resource Utilization
Purpose: To compare the actual hours logged by each resource (Utilized Effort) against their expected capacity (Available Effort).
Calculation: Available effort is calculated based on a standard 40-hour week, adjusted for the resource's allocation percentage.
Slicers: Filter the report dynamically by:

FY-Period-Week
Task (e.g., Review, Training, PTO)
Resource
Worked for Business

Report 2: Review Effort & Business Allocation
Purpose: To analyze what percentage of a resource's time is spent specifically on "Review" tasks and to see how many resources are contributing to each business unit.
Calculation: Review Effort % is calculated as (Total Review Hours in Period) / (8 hours * 20 days).
Slicers: Filter the report dynamically by:
FY-Period-Week
Resource
Worked for Business

3. Technology & Tools
Microsoft Excel: The primary platform for the dashboard.

Power Query (Get & Transform): Used for all ETL (Extract, Transform, Load) processes. This includes cleaning data, unpivoting tables, and merging the source files.

Power Pivot: Used for creating the backend data model, establishing relationships between tables, and writing DAX (Data Analysis Expressions) for complex calculations (Measures and Calculated Columns).

Note: For users of Excel 2013, the Power Query and Power Pivot add-ins must be installed and enabled separately. In modern versions of Excel (2016+), these tools are built-in.

4. How to Use This Solution
Open the Report File: Open the main Excel workbook (.xlsx) that contains this solution.
Update Data (Optional): If you have new data in your source CSV files, simply go to the Data tab in Excel and click the Refresh All button. All Power Query transformations and PivotTable reports will update automatically.
Interact with the Dashboard: Use the slicers provided on each report sheet to filter and analyze the data as needed.
