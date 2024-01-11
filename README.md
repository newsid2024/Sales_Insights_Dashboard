# Sales Insight Dashboard with PowerBI
## Sales Insights Project PowerBI Dashboard

This project, inspired by the Code Basics YouTube channel, focuses on creating a comprehensive PowerBI Dashboard for AtliQ Hardware, a company with branches across India dealing in computer hardware and peripherals. The Sales Director is grappling with challenges in understanding the business performance, leading to a decline in sales. The team aims to alleviate this by transforming raw data into visually intuitive representations to facilitate data-driven decision-making.

## Problem Statement

The Sales Director faces difficulty obtaining timely and comprehensible information from regional managers, who often struggle to interpret data from Excel files. This communication gap prompts the need for an interactive PowerBI Dashboard to streamline data analysis and enhance decision-making.

## Solution

To address the challenges, a dedicated team was assembled to implement the PowerBI Dashboard. The AIMS grid project management tool was employed to define the project's purpose, stakeholders, end results, and success criteria.

### AIMS Grid

![AIMS Grid](https://github.com/NotRamm/Sales-Insight-Dashboard-using-Power-BI/blob/master/Screenshots/AIMS%20grid%20sales%20insights.jpg)

## Project Implementation Steps

1. Utilized the AIMS grid for project planning.
2. Employed MySQL for data retrieval from the database into Power BI.
3. Conducted data cleaning in Power Query.
4. Executed the ETL process (Extract, Transform, Load).
5. Created measures for specific needs and utilized them for building visuals in PowerBI.
6. Standardized currency types in transactions through currency conversion.
7. Conducted data validation.
8. Implemented data modeling and visualization.

## Major Changes/Customizations

1. Resolved the '(blank)' issue for products by replacing the original products table with a modified version.
2. Merged the original 'sales_transaction' table with a new version containing additional data like profit margin and cost price.

### Insights

1. Over four years, the company generated a total revenue of ₹985M, with a profit margin of ₹24.7M (2.5%) and sales quantity of ₹2M. In 2020, revenue was ₹142M with a profit of ₹2.1M.
2. Delhi NCR led in revenue with ₹520M (52.8%), but the profit margin was only 2.3%. Bhubaneshwar in 2020 had the highest profit margin (10.48%), while Mumbai contributed the most to total profit (23.89%).
3. Bengaluru had the lowest profit margin of -20.8% and a minimal contribution to total profit (-0.3%).
4. Top customer Electricalsara Stores generated ₹413M in revenue, and the highest-grossing product was Prod318 with ₹69M in revenue.
5. Distribution products contributed ₹494M, and own-brand products contributed ₹494M over four years.
6. Revenue trend analysis highlighted a significant decrease in June 2020 compared to the previous year, with the lowest profit margin in April 2020.

## Key Learnings

1. Understanding real business datasets.
2. Writing analytical queries in MySQL.
3. Connecting databases to Power BI and cleaning/modifying data in Power Query.
4. Implementing practical DAX functions and measures.
5. Creating analytical visuals and reports.

## Final Result - Dashboard Screenshots

#### Dashboard KPI Page
![Dashboard KPI Page](https://github.com/NotRamm/Sales-Insight-Dashboard-using-Power-BI/blob/master/Screenshots/Sales%20Insight%20-%20Page%20KPI.png)

#### Dashboard Performance Insights
![Dashboard Performance Insights](https://github.com/NotRamm/Sales-Insight-Dashboard-using-Power-BI/blob/master/Screenshots/Sales%20Insight%20-%20Page%20Performance%20Insights.png)

#### Dashboard Profit Analysis
![Dashboard Profit Analysis](https://github.com/NotRamm/Sales-Insight-Dashboard-using-Power-BI/blob/master/Screenshots/Sales%20Insight%20-%20Page%20Profit%20Analysis.png)
