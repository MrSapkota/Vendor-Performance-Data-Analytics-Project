# Vendor-Performance-Data-Analytics-Project

Project Overview
This project presents an end-to-end data analytics pipeline focused on analyzing vendor and brand performance in the retail and wholesale industry. The goal is to optimize profitability and inventory efficiency by identifying underperforming brands, high-impact vendors, the effect of bulk purchasing on costs, inventory turnover, and profitability differences among vendors.

Features and Objectives
Automates data ingestion from raw CSV files into a SQLite database using Python ETL scripts.

Cleans and integrates fragmented data tables into an aggregated vendor-sales summary.

Performs Exploratory Data Analysis (EDA) and statistical analysis to identify business insights.

Analyzes vendor contribution, pricing strategies, inventory turnover, and profitability.

Visualizes findings with Power BI dashboards, including vendor rankings, purchase contributions, and inventory KPIs.

Supports actionable recommendations for vendor management, procurement, sales, operations, and finance teams.

Project Structure
data/ : Raw CSV datasets for purchases, sales, vendor invoices, and prices.

ingestion_db.py : Python ETL script for loading CSV data into SQLite database.

data_cleaning.py : Scripts/functions for cleaning and aggregating data into summary tables.

vendor_performance_analysis.ipynb : Jupyter notebook for EDA, analysis, and statistical testing.

powerbi/ : Power BI report files and dashboards for visualization.

logs/ : Logs from ETL and analysis scripts capturing process info and debugging.

inventory.db : SQLite database file (if included).

README.md : This documentation file.

Installation & Requirements
Python 3.x

Required Python libraries: pandas, numpy, sqlalchemy, matplotlib, seaborn, scipy, sqlite3

Power BI Desktop (for viewing dashboards)

You can install Python dependencies via pip:

bash
pip install pandas numpy sqlalchemy matplotlib seaborn scipy
Usage Instructions
Place raw CSV files in the data/ directory.

Run ingestion_db.py to ingest data into the SQLite database.

Execute data_cleaning.py or run notebook cells in vendor_performance_analysis.ipynb to prepare data and perform EDA.

Open and explore the Power BI dashboards in the powerbi/ folder for interactive visualization.

Review logs in logs/ folder for detailed processing info.

Key Insights
Identification of underperforming but high-margin brands for targeted promotions.

Top vendors contribute over 70% of procurement spend; vendor dependency is a strategic risk.

Bulk purchasing lowers unit costs by up to 72%, encouraging volume increases.

Low inventory turnover ties up capital, highlighting slow-moving stock needing attention.

Profitability varies significantly between vendor performance groups, informing tailored strategies.

Contributions
Contributions and improvements are welcome! Please fork this repository, make your changes, and submit a pull request.

<img width="1165" height="617" alt="image" src="https://github.com/user-attachments/assets/b349fa09-33b3-446d-84d7-de943376f239" />

<img width="1110" height="558" alt="image" src="https://github.com/user-attachments/assets/418f3801-88b9-4ab6-864e-a6994b393790" />


