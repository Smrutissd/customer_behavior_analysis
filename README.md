# 📊Customer Behavior Analysis  
📝 Overview
This project demonstrates a complete data analytics lifecycle—from importing and exploring raw data to generating business insights using dashboards and reports. It showcases skills in Python, SQL, PostgreSQL, data cleaning, exploratory data analysis (EDA), visualization, and business presentation.
The objective is to analyze the dataset, identify key trends, and summarize results through data-driven insights.

📂 Dataset
Format: .csv
Source: Public/Provided dataset
Contains records related to customer-based attributes such as demographics, transactions, and usage behavior (customize as needed)

Features include:
ID fields
Numerical variables
Categorical fields
Timestamps
Dataset preprocessing and transformations were performed before analysis.

🛠 Tools & Technologies Used:
Data Loading & EDA - Python (Pandas, NumPy, Matplotlib/Seabo)
Data Cleaning	- Python
Database Queries -	PostgreSQL, SQL
Data Storage	- PgAdmin4
Visualization -	Microsoft Power BI
Presentation	- Gamma App
Reporting -	PDF/Text Format

🧪 Project Steps
1️⃣ Data Import & Initial Exploration
Loaded dataset using pandas
Checked structure, size, data types
Identified null values and inconsistent formats
2️⃣ Exploratory Data Analysis
Performed:
Summary statistics
Distribution analysis
Trend detection
Outlier analysis
Correlation study
Charts Used:
Histograms
Bar charts
Box plots
Heatmaps
3️⃣ Data Cleaning
Actions taken:
✔ Handling missing values
✔ Removing duplicates
✔ Standardizing formats
✔ Encoding categorical variables
✔ Feature extraction (if applicable)
4️⃣ SQL Integration
Stored cleaned data in PostgreSQL
Querying through SQL (Examples):
Aggregations
Filtering
Grouping
Joins
Data validation was also performed through SQL queries.
5️⃣ Dashboard Creation
A Power BI dashboard was created to highlight:
Key metrics
Graphical summaries
Interactive filters
Business performance insights
It includes:
KPIs | Charts | Slicers | Drill-downs

Results & Insights
📌 Avg purchase amount is ~$59.76, with consistent spending across customer groups.
➡ Subscribers generate more revenue per user despite being fewer in number. 
➡ Top-rated products include Gloves, Sandals, Boots, Hats, and Skirts.
➡ Most purchased items vary by category (e.g., Jewelry, Blouse, Sandals).
➡ Repeat buyers are strongly linked with subscriptions, indicating loyalty.
➡ Express shipping users spend slightly more than standard shipping customers.
➡ Some products are highly dependent on discounts, showing price sensitivity.
➡ Middle-age groups contribute the highest revenue, making them a key target audience.

🖥 How to Run
Requirements - Python 3.x, PostgreSQL installed, Power BI Desktop
Steps:
➡Clone this repository
git clone https://github.com/Smrutissd/customer_behavior_analysis.git
➡Install Python libraries
pip install -r requirements.txt
➡Run Python script/notebook for cleaning and EDA
python analysis.py
➡Create a PostgreSQL database & import cleaned data
➡Run SQL queries using PgAdmin4
➡Open Power BI dashboard file (.pbix)

📎 Deliverables
✔ Cleaned dataset
✔ EDA notebook/script
✔ SQL query file
✔ Power BI dashboard
✔ Project report
✔ Gamma-generated PPT

⭐ Key Skills Demonstrated
Data Cleaning
Exploratory Data Analysis
SQL Querying
Dashboard Creation
Presentation & Reporting
