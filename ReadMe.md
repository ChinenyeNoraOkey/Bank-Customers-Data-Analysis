# Bank Customer Churn Data Analysis

## Problem Statement

As a Data Analyst, I am tasked with addressing the bank’s growing concern over customer attrition. Despite having a large customer base, the bank lacks clarity on why certain customers choose to leave while others remain loyal. There is no existing data-driven framework to assess which demographics, financial behaviors, or engagement patterns contribute to churn. Without these insights, the bank risks making uninformed decisions that could lead to continued customer loss and missed opportunities for growth. This analysis aims to bridge that gap by exploring the underlying factors influencing customer behavior and churn.


## Objective

- Analyze this customer dataset to uncover valuable insights for the bank's decision-making process.

- focus on understanding the demographic

- Understanding financial characteristics of the bank's customers

- Identifying trends and patterns in customer engagement

- highlight potential areas for business improvement e.g., customer retention or service optimization.


## Dataset

- Source: `Bank_Churn_Messy.xlsx`

- Sheets: Customer_Info & Account_Info

- Columns In Customer_Info: CustomerId, Surname, CreditScore, Geography, Gender, Age, Tenure, EstimatedSalary

- Columns In Account_Info: CustomerId, Balance, NumOfProducts, HasCrCard, Tenure, IsActiveMember, Exited

- Merged on `CustomerId`


## Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- VS Code
- Git & GitHub


## Key Insights

-  The overall churn rate is approximately 20.4%.

-  Inactive members are more likely to churn than active ones.

-  Customers with multiple products (especially 2+) showed higher churn rates.

-  Churned customers had, on average, higher account balances than those who stayed.

-  Customers with low credit scores are more likely to churn.

-  Specific age groups (especially 36–45 years old) and certain geographies showed higher churn patterns.

These insights reveal both engagement and risk factors that the bank can act upon.


## Recommendations

- Retention programs should be tailored for inactive and multi-product customers

- Educate and support customers with low credit scores to build trust and engagement

- Evaluate satisfaction and usability of bundled products to address multi-product churn

- Monitor churn-prone regions and age groups more closely to personalize communication and service