## E-commerce Customer Behavior Analysis Using Python and SQL.
A data analysis project exploring customer purchase patterns, churn behavior, and 
product performance using Python and SQL. The goal is to help businesses understand how customer
demographics and behaviors affect revenue, loyalty, and returns.

## Key Insights 
1. Customers aged 38-50, especially females, spend the most overall representing the platform's
   most valuable demographic.
2. Clothing and Books lead sales, followed by Electronics and Home products.
3. Chi-square testing revealed a significant relationship between total purchase amount and
   likelihood of returns. High spenders are more likely to return items-possibly due to higher quality
   expectations.
4. Churn Analysis:
   Linear Regression model: Churn = -0.00108 * Age + 0.205
   Older customers are slightly less likely to churn, while younger customers are more likely to
   leave.
5. Older customers return products more but remain loyal. Younger customers return less but churn
   faster- showing less brand loyalty.
6. Based on Total Purchase Amount, Age, and Quantity, customers were grouped into:
   Cluster 0: Low spenders, young age
   Cluster 1: Mid-range buyers, average age
   Cluster 2: High-value customers, older age

## Business Impact
1. Retention efforts should focus on younger customers, who are more likely to churn.
2. Personalized marketing campaigns by cluster can increase conversion and lifetime value.

## Tools & Techniques
1. Python: Pandas, Matplotlib, Seaborn, Scikit-learn
2. SQL: For querying and filtering customer transactions
3. Machine Learning: Linear Regression, Chi-square test, K-Means clustering

If you want explore deeper insights into this project, then check it out here
[https://medium.com/@kekelibeddy1553/e-commerce-customer-behavioral-analysis-using-python-and-sql-766c61df3b05]

