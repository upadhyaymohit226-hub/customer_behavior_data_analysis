# customer_behavior_data_analysis
data_analytics project showcasing behavior analysis using python , sql  and power bi

This project demonstrates a complete data analytics workflow — from raw data ingestion to a polished presentation. It covers exploratory data analysis in Python, structured querying across multiple SQL databases, interactive dashboard creation in Power BI, a written insights report, and a visual presentation built in Gamma.
📂
Dataset
Attribute	Detail
Source	 CSV
Format	.csv
Domain	Sales 
Key Columns	gender,age_group,category,customer_id,purchase_amount,Subscription_status etc
🛠
Tools & Technologies
Python 
pandas
Jupyter Notebook
MySQL
SQL Server
Power BI Desktop
Gamma (PPT)
🔢
Project Steps
Step 1

Load Dataset in Python

Step 2

Exploratory Data Analysis

Step 3

Data Cleaning & Preprocessing

Step 4

SQL Queries (PG / MySQL / MSSQL)

Step 5

Power BI Dashboard

Step 6

Insights Report (PDF/Word)

Step 7

Presentation via Gamma

📊
Dashboard
Built in Power BI Desktop. The dashboard includes:

• KPI cards (Total Revenue, Avg Order Value, Customer Count)
• age group revenue chart
• Category-wise bar chart
•  slicer filters
• Drill-through for detailed customer view

File: /dashboard/project_dashboard.pbix

✅
Key Results
Null values resolved
▶
How to Run
Copy
# 1. Clone the repo
git clone https://github.com/yourusername/data-analytics-project.git
cd data-analytics-project

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run EDA notebook
jupyter notebook notebooks/eda.ipynb

# 4. Run SQL scripts
# Open sql/queries.sql in your DB client (PgAdmin / MySQL Workbench / SSMS)

# 5. Open Power BI dashboard
# Open dashboard/project_dashboard.pbix in Power BI Desktop
📁
Folder Structure
project/
├── data/
│   └── dataset.csv
├── notebooks/
│   ├── eda.ipynb
│   └── cleaning.ipynb
├── sql/
│   └── queries.sql
├── dashboard/
│   └── project_dashboard.pbix
├── report/
│   └── insights_report.pdf
├── presentation/
│   └── project_slides.pdf
├── requirements.txt
└── README.md


