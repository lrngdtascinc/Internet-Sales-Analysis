# Internet-Sales-Analysis
Using Excel, Python, SQL, and Power BI to create a visual Internet Sales report requested by a Sales Manager.

## Project Overview
A sales manager is looking to improve the quality of the internet sales reports in order to track metrics alot easier.
What the sales manager is looking for is a dashboard where he can see how much of what product has been sold, over the 
period of 2020 to 2022, and to which clients in order to track how well his staff is adhering to the budget set in place.

## Deliverable 1): Restored Database & Cleaned Tables
In the first deliverable I downloaded and restored the Adventure Works 2022 Data warehouse and created a user under the creative name etl to be able to connect to the data warehouse and run SQL queries in order to extract the data needed to build a Power BI sales report.
![SQL Server DW](https://github.com/lrngdtascinc/Internet-Sales-Analysis/blob/6226ffe45e33421e54359cea659df644ec1eab55/Creating%20SQL%20Server%20User.png)

## Deliverable 2): SQL Server to PgAdmin ETL Pipeline
In the second deliverable I utilized Python along with the pandas, pyodbc, psycopg2, and sqlalchemy libraries in order to create an etl pipeline to extract the tables necessary from SQL Server, transform the tables utilizing pandas with embedded SQL queries, and loading the transformed tables into Pgadmin to be used in my Power BI report.
![Jupyter Notebook]()
![Pgadmin query History]()



## Deliverable 3): Power BI Internet Sales Report
