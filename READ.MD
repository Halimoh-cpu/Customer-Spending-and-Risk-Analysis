
Project Overview
This project focuses on analyzing customer spending behavior and credit risk using transactional data. The goal is to transform raw datasets into actionable insights through data cleaning, modeling, and visualization.

Datasets Used
Customer Dataset → demographic details, credit score
Card Dataset → card type, credit limit
Transactions Dataset → transaction amount, merchant details, date

Step 1: Data Cleaning (Excel)
Converted raw datasets into structured Excel tables
Renamed columns using consistent naming conventions
Removed duplicate records (Customer & Card tables)
Checked for missing and inconsistent values
Standardized formats (dates, numeric values, text fields)

Step 2: Data Transformation (Power Query)
Loaded datasets into Power Query Editor
Cleaned and transformed columns:
Fixed data types (numbers, dates, text)
Standardized categorical values (e.g., gender, card types)
Created additional columns where necessary
Removed unnecessary fields
Ensured data consistency across all tables

Step 3: Data Modeling (Power BI)
Designed a star schema model:
Fact Table → Transactions
Dimension Tables → Customer, Card, Merchant
Established relationships:
Customer[id] → Transactions[client_id]
Card[id] → Transactions[card_id]
Merchant[merchant_id] → Transactions[merchant_id]
Ensured one-to-many relationships for accurate aggregation

Step 4: DAX Calculations
Created key measures including:
Total Spending = SUM(Transactions[amount])
Total Transactions = COUNT(Transactions[id])
Average Spending = DIVIDE([Total Spending], [Total Transactions])
Customer Count = DISTINCTCOUNT(Customer[id])

Step 5: Data Visualization
Built an interactive dashboard including:
KPI Cards:
Total Spending
Total Transactions
Average Spending
Total Customers
Charts:
Spending by Age Group
Credit Score by Age Group
Spending by Gender
Spending by Card Type
Spending by Merchant Category (MCC)
Spending Trend Over Time
Spending by Location
Filters (Slicers):
Use Chip
Merchant State
Card Brand

Key Insights
Majority of spending comes from customers aged 30–59
Spending is fairly balanced across genders
Certain merchant categories dominate transaction volume
Geographic patterns show concentration in specific regions
Credit score distribution provides insight into potential risk segments

Tools 
Power BI
Power Query
DAX
Excel

Outcome
The project successfully transformed raw transactional data into a structured analytical model and interactive dashboard, enabling clear visibility into customer behavior, spending patterns, and financial risk.
