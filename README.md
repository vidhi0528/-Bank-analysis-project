## Bank Risk Analysis Project
This project aims to develop a basic understanding of *risk analysis in banking and financial services.
We explore how data can be used to minimize the risk of financial loss when lending to customers.

## Objective
To understand how banks use data-driven decision making to reduce lending risk, identify patterns in customer behavior, and make more informed financial decisions.

## Tools & Technologies Used
- Excel: Initial data exploration and formatting
- MySQL: Database creation and structured querying
- Google Colab: Python-based Exploratory Data Analysis (EDA)
- Power BI: Interactive dashboard and visual storytelling

## Insights Discovered

--Deposits and Savings Behavior
The high correlation between Bank Deposits and Saving Accounts suggests that these may either measure overlapping financial behavior (e.g., total funds a customer keeps in the bank) or 
that people who actively deposit funds also tend to maintain or grow savings balances.

--Income, Age, and Accumulation
Moderate correlations of Age and Estimated Income with various balances (Superannuation, Savings, Checking) reflect a common financial lifecycle trend: 
higher income earners and older individuals often accumulate more savings, retirement funds, and may carry higher credit card balances or loans.

--Low Correlation with Properties Owned
Property ownership may depend on external factors (location, real estate market conditions, inheritance, etc.) 
that are not captured by these particular banking variables. Hence, we see weaker correlations here.

--Business vs. Personal Banking
Business Lending’s moderate link to Bank Loans suggests some customers may have both personal and business debts.
However, business lending is relatively uncorrelated with other deposit or property-related metrics, indicating it may serve a distinct subset of customers or needs.

## How to Run This Project
1. Set up MySQL and run Create_database.sql to generate the database and tables.  
2. Use Google Colab to run EDA_CaseStudy.ipynb for exploratory analysis.  
3. Open Banking_Analysis_Dashboard.pbit in Power BI to explore the interactive dashboard.  

## Conclusion
This project demonstrates how combining tools like SQL, Python, and Power BI can help derive meaningful insights from raw financial data and improve risk analysis practices in banking.

## About the Author
*Vidhi Potwar*  
Fresher Data Analyst passionate about analytics, visualization, and solving real-world problems with data.
