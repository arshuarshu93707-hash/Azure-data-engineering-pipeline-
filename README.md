# Azure Data Engineering Project - End to End

This project is for my learning and for jobs in Bangalore.

Tools I used: ADF, ADLS Gen2, Azure SQL, Power BI

What I did in this project:

1. Source - I took 100k+ records data from a public API using ADF Copy Activity
2. Raw Layer - Stored the raw json files in ADLS Gen2 container
3. Cleaning - Used ADF Data Flow (no code):
   - Filter - removed NULL values and duplicate rows
   - Derived Column - created new columns like total amount
4. Incremental Load - Used watermark column LastModifiedDate so only new data loads daily
5. Sink - Loaded clean data into Azure SQL Database
6. Dashboard - Connected Azure SQL to Power BI and made a report

This project is uploaded for my portfolio.
