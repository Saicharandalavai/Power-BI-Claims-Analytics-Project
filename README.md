End-to-End Insurance Claims Analytics Project

Project Overview
This project simulates a real-world data analytics workflow for an insurance company. The primary goal was to process raw claims data, perform in-depth analysis using SQL, and build a fully interactive executive dashboard in Power BI to monitor key performance indicators, identify trends, and detect potential fraud.

Tools Used
*   Database: MySQL
*   Data Analysis & Transformation: SQL (using MySQL Workbench)
*   Data Visualization & BI: Microsoft Power BI



Project Steps
1.  Data Generation: Created a large, realistic dataset (~28,000 rows across 3 tables) using a Python script.
2.  Database Management:Designed a relational database schema and loaded the raw data into MySQL.
3.  SQL Analysis:Wrote a single, comprehensive SQL query to join all tables, calculate new metrics like `DaysToSettle` and `CostVariance`, and add business logic for risk categorization. The results were exported to a clean CSV file.
4.  Dashboard Creation:Imported the final, analysis-ready data into Power BI to build an interactive dashboard.


 Final Dashboard
The final dashboard provides a 360-degree view of claims performance. It allows business users to:
*  Track high-level KPIs like total claim value and average settlement time.
*   Analyze claim trends by policy type and geography using interactive charts and maps.
*   Drill down into a detailed, filtered list of claims flagged for fraud investigation.

