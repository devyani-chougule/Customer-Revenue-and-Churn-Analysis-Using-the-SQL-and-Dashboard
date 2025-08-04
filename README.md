# Customer-Revenue-and-Churn-Analysis-Using-the-SQL-and-Dashboard
# SaaS Customer Analytics using SQL

This repository contains SQL scripts for analyzing customer behavior, revenue trends, retention, and churn in a SaaS-based business environment. The analysis is broken down into four key modules, each stored in a separate SQL file.

---

 📊 Key Analyses Covered

 1. Cohort Analysis  
Track customers by their signup month (cohort) and calculate their active lifespan.  
- Assign customers to cohorts  
- Measure retention over time  
- Prepare data for cohort heatmaps  

📄 File: `sql/customer-cohort-retention-sql.sql`

---

2. Lifetime Value (LTV) & Revenue  
Calculate customer revenue and lifespan to derive LTV.  
- Total revenue per customer  
- Lifespan in months  
- LTV per customer per month  

📄 File: `sql/customer-ltv-lifespan-sql.sql`

---

 3. Customer Spending Analysis  
Segment customers based on spending amount and categorize them into groups.  
- Total spending per customer  
- Spending group (High / Medium / Low)  
- Breakdown by country and customer segment  

📄 File: `sql/customer-spending-analysis.sql`

---

 4. Monthly Revenue, ARPU & Churn  
Analyze monthly financial KPIs and customer churn.  
- Monthly Recurring Revenue (MRR)  
- Average Revenue Per User (ARPU)  
- Monthly churned customers  

📄 File: `sql/mrr-arpu-churn-sql-analysis.sql`

---

📦 Dataset Assumptions

The analysis assumes the following tables:

- `customer.customers`: Contains customer IDs, signup and cancel dates, country, and segment.  
- `customer.transactions`: Contains transaction records with amount and date.  
- `customer.subscriptions`: Contains subscription start and end dates.

---

 🚀 How to Use

1. Load your dataset into MySQL or any compatible SQL engine.  
2. Open the relevant SQL file from the `/sql/` folder.  
3. Execute queries to analyze customer KPIs or export the results to BI tools like Power BI or Tableau.

---

 📈 Suggested Visualizations

- Heatmap: Cohort retention (Signup Month × Active Months)  
- Line Chart: MRR and ARPU trends  
- Donut/Bar: Spending Group by Segment  
- Funnel or Bar: Monthly Churned Customers

---

 🛠️ Tools Used

- MYSQL (MySQL Syntax)  
- Power BI or Tableau (optional, for dashboards)
---
