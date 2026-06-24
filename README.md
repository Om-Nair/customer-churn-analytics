\# Customer Churn Analytics



\## Overview



Customer churn represents a major challenge for subscription-based businesses because losing existing customers directly impacts recurring revenue and customer lifetime value.



This project analyzes customer behavior using the IBM Telco Customer Churn dataset to identify the factors driving churn, predict churn risk, and recommend targeted retention strategies.



The project combines exploratory data analysis, machine learning, and business-focused recommendations to demonstrate an end-to-end analytics workflow.



\---



\## Business Problem



A telecommunications company wants to understand:



\- Which customers are most likely to churn?

\- What factors drive churn behavior?

\- Which customer segments should be prioritized for retention efforts?

\- How much revenue is potentially at risk?



\---



\## Dataset



Source: IBM Telco Customer Churn Dataset



Records: 7,043 customers



Features include:



\- Customer demographics

\- Contract information

\- Billing information

\- Service subscriptions

\- Churn outcome



\---



\## Project Workflow



\### 1. Data Preparation



\- Data quality validation

\- Missing value treatment

\- Feature engineering

\- Categorical encoding



\### 2. Exploratory Data Analysis



Key findings:



\- Month-to-month customers exhibit significantly higher churn rates

\- Low-tenure customers are more likely to leave

\- Higher monthly charges are associated with increased churn risk

\- Contract structure is a stronger predictor than demographic characteristics



\### 3. Predictive Modeling



Models evaluated:



\- Logistic Regression

\- Random Forest Classifier



Performance metrics:



\- Accuracy

\- Precision

\- Recall

\- F1 Score



\### 4. Business Recommendations



Target retention efforts toward:



\- Month-to-month subscribers

\- New customers

\- High monthly charge accounts

\- Customers exhibiting multiple churn risk indicators



\---



\## Key Insights



\### Contract Type Drives Retention



Customers with longer-term contracts are substantially less likely to churn.



\### Early Customer Lifecycle Is Critical



Most churn risk is concentrated among customers with lower tenure.



\### Revenue Protection Opportunity



Targeted retention strategies focused on high-risk customer segments can help preserve recurring revenue and improve customer lifetime value.



\---



\## Repository Structure



```text

notebooks/

├── 01\_churn\_analysis\_and\_modeling.ipynb

└── 02\_business\_recommendations.ipynb



assets/

└── feature\_importance.csv



dashboard/

```



\---



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Scikit-Learn

\- Matplotlib

\- Jupyter Notebook

\- Git

\- GitHub



\---



\## Future Improvements



\- XGBoost implementation

\- Customer risk scoring dashboard

\- Automated retention recommendation engine

\- Power BI executive dashboard

