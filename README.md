Retail Customer Behavior Analytics Pipeline
🚀 Project Overview

This project demonstrates an end-to-end data analytics pipeline designed to extract actionable business insights from a dataset of 3,900 consumer transactions. I transformed raw data into a structured relational database and built an interactive Power BI dashboard to visualize key performance indicators (KPIs) and demographic spending patterns.
🛠️ Tech Stack

    Data Processing: Python (Pandas)

    Database Management: PostgreSQL (pgAdmin 4)

    Data Visualization: Power BI Desktop

    Database Connectivity: SQLAlchemy & Psycopg2

📈 Key Insights & Business Value

    Revenue Intelligence: Analyzed a total revenue of $233.07K, identifying core growth drivers.

    Demographic Segmentation: Implemented server-side data binning to categorize shoppers into generational cohorts (Gen Z, Millennials, Gen X, Seniors).

    Loyalty Analysis: Discovered that 43% of customers rely on promotional codes, highlighting an opportunity for a non-discount-based loyalty program.

    Payment Optimization: Identified that high-ticket items (Outerwear/Footwear) are predominantly purchased via Credit Card, signaling a need for targeted EMI offers.

🏗️ Data Pipeline & Technical Hurdles
1. Data Cleaning (Python)

Standardized raw headers into snake_case (e.g., purchase_amount_usd) to ensure seamless integration with the SQL environment and avoid escape-character errors in Power BI.
2. Relational Schema (PostgreSQL)

Migrated 3,900 records into a structured PostgreSQL database. Utilized CASE statements to perform server-side data transformation for age segmentation.
3. BI Connectivity & Troubleshooting

Successfully resolved SSL Handshake and Untrusted Certificate errors during the Power BI integration. Configured the BI tool to trust local self-signed certificates, demonstrating real-world network troubleshooting skills.
📊 How to Use

    SQL: Run the scripts in the /sql folder to set up the database schema and views.

    Power BI: Open the .pbix file to explore the interactive dashboard.

    Python: Run the Jupyter Notebook to see the ETL (Extract, Transform, Load) process.
