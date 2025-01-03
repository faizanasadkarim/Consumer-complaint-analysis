Consumer Complaints Data Analysis
This repository contains a detailed analysis of consumer complaints data using Excel. The project focuses on data cleaning, combining datasets, working with dates, and generating insightful reports and dashboards to help understand the customer complaints landscape, resolution process, and reporting at various levels (e.g., company, product, etc.).

Project Overview
The analysis uses consumer complaints data, which includes details such as state codes, complaint issues, resolution times, and company information. The project covers the following key areas:

Data Preparation: Merging and cleaning datasets, extracting relevant details.
Data Analysis: Identifying trends, handling missing data, and assessing complaint resolution.
Reporting: Generating summary reports at both company and issue levels.
Dashboard Creation: Visualizing the complaint data to uncover key insights.
Key Objectives:
Understand complaint trends over time and across different companies and products.
Analyze the timeliness and effectiveness of complaint resolutions.
Create actionable insights for customer support teams to prioritize complaints.
Tasks Breakdown
Task 1: Data Preparation and Combining Datasets
Create Columns:

Add STATE and CODE columns to the State_Code_Name worksheet.
Extract and transform data from JSON format into a tabular structure using Excel functions like VLOOKUP.
Data Mapping:

Create a State_Name column in the Consumer_Complaints worksheet.
Map State_Code to State_Name using data from the State_Code_Name worksheet.
Count Missing Data:

Calculate the number of records with missing state names (i.e., #N/A values).
Create a summary table highlighting complaints with unmapped state names.
Analyze the causes of missing state data.
Task 2: Working with Dates
Calculate Resolution Time:

Determine the resolution time (in days) for each complaint based on the complaint and resolution dates.
Year and Quarter Columns:

Add a YEAR column to extract the year from the complaint received date.
Add a QTR column to determine the fiscal quarter (Q1, Q2, Q3, Q4) based on the complaint date.
Data Cleaning:

Ensure that all date columns are in a valid format (e.g., mm/dd/yyyy or dd-mm-yyyy).
Task 3: Reporting at Company Level
Company-wise Complaints:

Summarize the total number of complaints for each company.
Timely Response:

Calculate the number and percentage of complaints that did not receive a timely response.
Disputed Complaints:

Calculate the number and percentage of complaints marked as disputed.
Average Delay:

Calculate the average delay (in days) in resolving complaints.
Task 4: Reporting and Visualization
Top 5 Companies with Complaints:

Identify and display the top five companies with the highest number of complaints.
Top 5 Complaint Issues:

Identify and display the top five issues leading to complaints.
Monthly Trends:

Create a line/area chart to visualize the trend of complaints over time on a monthly basis.
Task 5: Dashboard Creation
Key Performance Indicators (KPIs):

Display KPIs such as total complaints, timely responses, and average resolution time, including Year-over-Year (YoY) comparisons.
Proportions by Product and Channel:

Show the breakdown of complaints by product type and the channel through which the complaint was filed.
Priority Complaints:

Visually highlight complaints that need to be prioritized based on urgency and other factors.
Monthly Trends:

Display a line/area chart showing the monthly trend of complaints over time.

1. Data Files
All data for analysis is stored in the Consumer_Complaints and State_Code_Name worksheets. Ensure the data is properly formatted before proceeding with the analysis.

2. Analysis Steps
Follow the task breakdown outlined above to perform data preparation, analysis, and reporting. Key Excel features used include:

Pivot Tables
VLOOKUP
COUNTIF
Charts
IFS
3. Report Creation
After completing the analysis, use Excel to create reports for each task, such as company-wise summaries and issue-wise complaints. Add relevant charts and summaries as necessary.

4. Dashboard Creation
Create a new worksheet called Report_Task5 to build the dashboard and display KPIs, trends, and other visual insights.

Tools Used
Excel: For data cleaning, analysis, pivot tables, charts, and dashboards.
Excel Formulas:
VLOOKUP, COUNTIF, DATEDIF, YEAR, MONTH, etc.
Data transformations and calculations.
Inferences
The analysis helps to identify key trends and KPIs such as the average resolution time and the proportion of timely responses across different companies.
Insights from the analysis assist customer support teams in prioritizing complaints and improving overall response times.
The dashboard offers a comprehensive view of complaint trends, product performance, and response effectiveness.
Acknowledgements
The data for this project was sourced from publicly available datasets.
Special thanks to contributors and the open-source community for the tools used in data cleaning and analysis.
