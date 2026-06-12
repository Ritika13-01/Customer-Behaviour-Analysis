**📊 Customer Behaviour Analysis & Dashboard**
**📌 Project Overview**

This project focuses on analyzing customer shopping behavior using Excel data, performing Exploratory Data Analysis (EDA), answering key business questions using SQL, and building an interactive dashboard to visualize insights.
<a><img width="1307" height="737" alt="image" src="https://github.com/user-attachments/assets/47be55ca-4c51-49cc-a301-15cb4c66049b" /></a>

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

SQL was used extensively in this project to extract meaningful insights from the customer dataset and answer key business questions. By writing structured queries, we were able to aggregate, filter, and segment the data efficiently, supporting both exploratory analysis and dashboard development.

The analysis began with basic data exploration to understand the structure and contents of the dataset. From there, progressively advanced queries were used to uncover patterns in customer behavior, spending habits, and product performance.

Key areas of analysis included revenue distribution, customer segmentation, product ratings, discount impact, and behavioral trends across different demographics such as gender, age group, and subscription status.

Using SQL, we were able to:

Compare revenue contribution across genders to identify high-value customer segments
Identify customers who used discounts but still spent above average, highlighting valuable promotional targets
Analyze top-rated products based on customer reviews to understand product satisfaction
Compare spending patterns across different shipping methods
Evaluate whether subscription status influences customer spending and revenue generation
Determine which products are most influenced by discounts
Segment customers into New, Returning, and Loyal categories based on purchase history
Identify top-performing products within each category using ranking techniques
Analyze whether repeat buyers are more likely to subscribe
Measure revenue contribution across different age groups

Advanced SQL concepts such as subqueries, Common Table Expressions (CTEs), aggregate functions, conditional logic (CASE statements), and window functions (ROW_NUMBER) were used to perform deeper analysis and segmentation.

These SQL queries played a crucial role in:

Validating insights derived during EDA
Powering the metrics displayed in the dashboard
Enabling data-driven decision-making

Overall, SQL served as a backbone for transforming raw transactional data into structured insights that directly informed the visualizations and business conclusions of this project.

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

**📎 Conclusion**
This project demonstrates how raw customer data can be transformed into meaningful insights using EDA, SQL, and visualization tools. The dashboard enables stakeholders to quickly understand customer behavior and make data-driven decisions.
