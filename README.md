Customer Data Analytics Project
Overview

This project demonstrates a complete data analytics workflow, starting from raw customer data in Excel and ending with an interactive Power BI dashboard.

The project covers data cleaning, database management, SQL analysis, and data visualization to transform raw data into meaningful insights.

Project Workflow
1. Data Collection
Imported customer dataset from an Excel file.
Examined data quality and structure.
2. Data Cleaning & Preprocessing (Python)
Handled missing values.
Removed duplicates.
Corrected data types.
Performed data transformations.
Prepared a clean dataset for analysis.
3. Database Management (PostgreSQL)
Imported the cleaned dataset into PostgreSQL.
Created tables and managed data storage.
Executed SQL queries for data analysis and validation.
4. Data Visualization (Power BI)
Connected Power BI to PostgreSQL.
Built an interactive dashboard.
Created visualizations to analyze customer behavior and business performance.
Tech Stack
Python
Pandas
NumPy
Jupyter Notebook
Database
PostgreSQL
Visualization
Power BI
Data Source
Microsoft Excel
Project Structure
├── Project.ipynb      # Data cleaning and preprocessing
├── DA.sql             # SQL queries and database operations
├── DA.pbix            # Power BI dashboard
├── Dataset.xlsx       # Source customer dataset
└── README.md
Key Features
End-to-end ETL workflow
Data cleaning using Python
Database integration with PostgreSQL
SQL-based analysis
Interactive Power BI dashboard
Business insights from customer data
Dashboard Insights

The dashboard helps analyze:

Customer purchasing behavior
Revenue trends
Customer segmentation
Sales performance metrics
Key business KPIs
How to Run
Python
Open Project.ipynb

Install required libraries:

pip install pandas numpy openpyxl
Run all notebook cells.
PostgreSQL
Create a database.

Execute the SQL script:

\i DA.sql
Power BI
Open DA.pbix.
Refresh the data connection.
Explore the dashboard.
Author

Vinal Patil

Data Analytics Project using Python, PostgreSQL, and Power BI.
