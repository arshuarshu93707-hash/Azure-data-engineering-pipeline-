# Azure Data Engineering - End to End Pipeline | Bangalore

## 🎯 Objective
Built an end-to-end data pipeline for 100k+ records to get Data Engineer role in Bangalore (6 LPA).

## 🛠️ Tech Stack
- Azure Data Factory (ADF) - Copy Activity, Mapping Data Flow
- ADLS Gen2 - Data Lake Storage
- Azure SQL Database
- Power BI

## 📊 Architecture
API -> ADF Copy Activity -> ADLS Gen2 (Raw Zone) -> ADF Data Flow (Filter, Derived Column) -> Azure SQL (Clean Zone) -> Power BI Dashboard

## ✅ What I Did
1. Ingested data from Public API using ADF Copy Activity
2. Stored raw JSON/CSV in ADLS Gen2
3. Cleaned data using ADF Mapping Data Flow:
   - Filter Transformation: Removed NULL values
   - Derived Column: Created new calculated columns
4. Implemented Incremental Load using Watermark Column (only new data loads daily)
5. Loaded final data into Azure SQL Database
6. Created Power BI report on top of it

## 📸 Screenshots
(Add your ADF pipeline screenshots here - upload via Add file button)

## 👩‍💻 About Me
B.Tech AI&ML (2026) | Looking for Azure Data Engineer / Data Analyst roles in Bangalore | Immediate Joiner

LinkedIn: (Add your LinkedIn link)
