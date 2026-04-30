📊 Customer Shopping Behavior Analysis
🔍 Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into purchasing patterns, customer segmentation, and revenue drivers.

The goal is to enable data-driven business decisions by combining Python, SQL, and Power BI for end-to-end analytics.

📁 Dataset
Total Records: 3,900 transactions
Features: 18 columns
Data Includes:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Product, Category, Amount, Season, Size, Color)
Behavioral data (Discounts, Purchase Frequency, Ratings, Shipping Type)
Data Quality:
Missing values handled (Review Ratings imputed using median by category)
Redundant fields removed
Standardized column naming
🛠️ Tools & Technologies
Python (Pandas, NumPy) – Data cleaning & feature engineering
PostgreSQL – Data storage & SQL analysis
SQL – Business queries & insights extraction
Power BI – Interactive dashboard & visualization
AI Tools – Presentation (PPT) generation
⚙️ Project Steps
1. Data Loading & Cleaning (Python)
Loaded dataset using Pandas
Handled missing values and inconsistencies
Standardized column names
Created new features:
Age groups
Purchase frequency
2. Data Storage (PostgreSQL)
Connected Python to PostgreSQL
Loaded cleaned dataset into database
3. Data Analysis (SQL)
Revenue analysis by gender
Subscriber vs non-subscriber comparison
High-value discount users
Product performance (top-rated, best-selling)
Shipping behavior analysis
Customer segmentation (New, Returning, Loyal)
4. Visualization (Power BI)
Built interactive dashboard with:
Revenue trends
Customer segments
Product insights
Shipping & discount analysis
5. Reporting & Presentation
Created a structured business report
Developed executive-level presentation using AI
📊 Dashboard Highlights
Revenue breakdown by customer segment
Subscriber vs non-subscriber performance
Top-performing products
Discount impact on revenue
Customer demographics insights
📈 Key Results
Subscribers have higher average spend
Express shipping users contribute higher revenue
Discounts increase sales volume but impact margins
Loyal customers drive maximum revenue contribution
Repeat buyers show higher likelihood of subscription
🚀 How to Run
Prerequisites
Python (3.x)
PostgreSQL
Power BI Desktop
Steps
Clone the repository
Load dataset into Python
Run data cleaning and transformation scripts
Connect Python to PostgreSQL and load data
Execute SQL queries for analysis
Open Power BI file to explore dashboard
💡 Business Recommendations
Promote subscription programs to increase retention
Implement loyalty programs for repeat customers
Optimize discount strategies to protect margins
Focus marketing on high-value customer segments
Highlight top-performing products in campaigns
