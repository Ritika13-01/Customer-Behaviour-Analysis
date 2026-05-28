**📊 Customer Behaviour Analysis & Dashboard**
**📌 Project Overview**

This project focuses on analyzing customer shopping behavior using Excel data, performing Exploratory Data Analysis (EDA), answering key business questions using SQL, and building an interactive dashboard to visualize insights.

The goal is to uncover patterns in customer purchasing habits, segment behavior, and provide actionable insights for business decision-making.

**🎯 Objectives**
Understand customer demographics and purchasing trends
Analyze revenue and sales distribution across categories
Evaluate the impact of subscription status on customers
Identify high-performing customer segments
Build a visual dashboard for quick business insights

**📂 Dataset**
Source: Excel dataset (customer_shopping_behavior.csv)
Contains:
Customer demographics (age, gender)
Purchase details (category, amount)
Subscription status
Shipping preferences
Review ratings

**🔍 Exploratory Data Analysis (EDA)**

EDA was performed to clean, explore, and understand the dataset.

Key Steps:
Data cleaning (handling null values, formatting)
Data type corrections
Summary statistics
Distribution analysis
Category-wise and demographic analysis
Insights from EDA:
Majority of customers are non-subscribers (~73%)
Clothing generates the highest revenue and sales
Young Adults contribute the most to revenue
Average purchase amount is around $59.76
Average review rating is 3.75

**🛢️ SQL Analysis**

SQL was used to answer key business questions and validate insights.

Sample Questions Answered:
What is the total revenue by category?
Which age group contributes the most to sales?
What is the average purchase amount?
How does subscription status affect purchasing behavior?
Which category has the highest number of orders?
Example Query:
SELECT category, SUM(purchase_amount) AS total_revenue
FROM customer_data
GROUP BY category
ORDER BY total_revenue DESC;

**📊 Dashboard Overview**

The dashboard provides a comprehensive view of customer behavior:

**Key Metrics:**
Total Customers: 4K
Average Purchase Amount: $59.76
Average Rating: 3.75
Visualizations:
Subscription distribution (Donut Chart)
Revenue by category (Bar Chart)
Sales by category
Revenue by age group
Sales by age group
Filters Available:
Subscription Status
Gender
Category
Shipping Type

**🧰 Tools & Technologies**
Excel / CSV – Data source
Python (Pandas, Matplotlib/Seaborn) – EDA
SQL – Data querying & analysis
Power BI / Tableau (or similar) – Dashboard creation

**📈 Key Business Insights**
Clothing dominates both revenue and sales volume
Non-subscribers form the majority but present an opportunity for conversion
Younger customers are the most valuable segment
Accessories and footwear show moderate performance and growth potential

**🚀 Future Improvements**
Add customer lifetime value (CLV) analysis
Build predictive models (purchase prediction, churn analysis)
Integrate real-time data pipelines
Enhance dashboard interactivity

**📎 Conclusion
**
This project demonstrates how raw customer data can be transformed into meaningful insights using EDA, SQL, and visualization tools. The dashboard enables stakeholders to quickly understand customer behavior and make data-driven decisions.
