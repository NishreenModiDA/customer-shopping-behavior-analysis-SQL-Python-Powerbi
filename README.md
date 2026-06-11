# Customer Shopping Behavior Analysis
SQL, Python, and Power BI projects.

📋 Overview
This end-to-end data analytics project focuses on understanding customer shopping behavior and identifying key purchasing trends. By leveraging an entire data pipeline—from extraction and cleaning to database querying and interactive visualization—this project delivers actionable insights to optimize marketing strategies and enhance customer retention.

📊 Dataset
Name: Retail Customer Behavior and Shopping Trends Dataset

Source: [Insert link to dataset, e.g., Kaggle]

Description: The dataset contains customer-level transaction data, including demographics (age, gender), purchasing history (item purchased, category, purchase amount), location, and behavioral metrics (frequency of purchases, review ratings, subscription status).

🛠️ Tools & Technologies
Data Processing & EDA: Python (Pandas, NumPy, Matplotlib, Seaborn)

Database Management: SQL (PostgreSQL / MySQL / SQL Server)

Data Visualization: Power BI

Reporting & Presentation: Gamma App (AI-generated PPT) & PDF Report

🚀 Project Steps
1. Data Loading & Exploratory Data Analysis (EDA)
Imported the raw dataset using Python.

Performed initial data profiling (.info(), .describe()) to understand data types, distributions, and summary statistics.

Visualized key distributions and correlations using Seaborn and Matplotlib.

2. Data Cleaning & Transformation
Handled missing values, duplicates, and anomalous data points.

Standardized column names and data formatting for seamless database injection.

Exported the cleaned data into a structured CSV format ready for relational database storage.

3. Database Management & SQL Querying
Designed the database schema and created tables within the SQL database environment.

Staged and populated the cleaned dataset into the database.

Authored complex SQL queries (aggregations, joins, window functions) to extract high-level business metrics such as:

Customer lifetime value (CLV) segments.

Top-performing product categories by region.

Seasonal sales trends and purchasing frequency patterns.

4. Interactive Power BI Dashboard
Connected Power BI to the data source and built a robust data model.

Developed key performance indicators (KPIs) and interactive visualizations.

Designed dynamic filters (Slicers) for age groups, regions, and product categories to allow stakeholders to drill down into the insights.

5. Reporting & Stakeholder Presentation
Compiled a comprehensive, structured data analysis report detailing the methodology and findings.

Utilized Gamma to generate an executive-ready PowerPoint presentation summarizing the project’s strategic recommendations.

📉 Dashboard & Insights
Key Visualizations Include:
Demographic Breakdown: Sales distribution by gender and age cohort.

Sales Performance: Total revenue and average order value (AOV) tracking.

Behavioral Analysis: Impact of subscription status and discount usage on total spend.



Key Results & Findings:
Finding 1:  Customers with subscriptions spend 25% more on average per transaction than non-subscribers.

Finding 2:  The highest revenue-generating category is Clothing, driven primarily by seasonal shifts in the Fall.

Finding 3:  Direct marketing campaigns should target the 25-35 age demographic in regional hubs where purchase frequency is highest.
