#Churn Analysis & Visualization on Power BI

##Project Objectives 

The goal of this project is to analyze customer churn using PostgreSQL, Power BI, and Excel. The project aims to identify key drivers of churn and visualize these insights to help businesses improve retention strategies

## Dataset

The dataset used for this project is the [retention_data.csv](./retention_data.csv).

##Key Questions (KPIs)

The project aims to answer the following business questions:
•	Churn Rate by Gender: How does churn vary between male and female customers?
•	Churn by Contract Type: What churn patterns exist across different contract types?
•	Revenue by Payment Method: How is total revenue distributed across payment methods?
•	Tenure vs. Churn: Is there a relationship between customer tenure and churn rates?
•	Senior Citizen Impact: Do senior citizens have a higher churn rate?
•	Service Usage: What is the distribution of internet and streaming service usage?


## Power BI Report

The Power BI report for this project is available in the [Retention Analysis.pbix](./Retention%20Analysis.pbix) file.

The Power BI dashboard presents several visualizations:
•	Churn Rate by Gender: Bar chart to compare churn between male and female customers.
•	Churn by Contract Type: Pie chart visualizing churn rates across different contract types.
•	Revenue by Payment Method: Pie chart representing revenue distribution by payment methods.
•	Monthly vs. Total Charges: Scatter plot comparing monthly charges vs. total charges.
•	Churn vs. Tenure: Line chart illustrating churn rate over customer tenure.
•	Service Usage: Stacked bar chart showing internet and streaming service usage.

##Process

The analysis followed these key steps:
1.	Data Preprocessing: Cleaned and transformed the dataset to handle missing values and adjust data types.
2.	SQL Queries: Used PostgreSQL to write queries that aggregate data on churn rates, revenue, contract types, etc.
3.	Power BI Visualization: Created interactive dashboards to visualize the analysis and identify trends.
4.	Excel Analysis: Utilized Excel for additional calculations and data validation before visualization in Power BI.

##Project Insights

#Key insights from the analysis:
•	Churn by Gender: Gender differences in churn rates suggest a targeted retention approach may be necessary.
•	Churn by Contract Type: Month-to-month contracts show a higher churn rate compared to long-term contracts.
•	Revenue Analysis: Payment methods like credit cards contribute significantly to total revenue, suggesting potential focus areas for marketing.
•	Tenure vs. Churn: Newer customers have higher churn rates, pointing to a need for early-stage retention strategies.
•	Senior Citizen Analysis: Senior citizens show higher churn, indicating possible improvements in service offerings.
•	Service Preferences: A significant number of customers use internet and streaming TV services, which could guide future product development.

##Final Conclusion

This project successfully identified key drivers of customer churn using SQL, Power BI, and Excel. By analyzing churn across various dimensions, businesses can develop more targeted strategies to reduce churn and increase retention. Visualizing these patterns using Power BI makes the insights accessible and actionable for business decision-makers.

#Next Steps:
•	Develop targeted retention strategies based on churn drivers.
•	Improve customer experience for at-risk demographics such as senior citizens.
•	Regularly monitor churn trends and test the effectiveness of retention strategies.
