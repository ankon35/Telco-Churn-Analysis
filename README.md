
# Customer Churn Analysis Project  

## Overview  
This project focuses on analyzing customer churn patterns using a dataset of **7,043 customer records**. The analysis helps identify key factors influencing churn, providing insights to improve customer retention strategies. Various techniques in **Python (Pandas, Matplotlib, Seaborn)** were used to conduct Exploratory Data Analysis (EDA) and visualize churn-related trends.

📄 **[Explore the Full Jupyter Notebook](https://github.com/ankon35/Telco-Churn-Analysis/blob/main/Python_Data_Analysis.ipynb)**

---

## Dataset  
- **Total Records**: 7,043  
- **Columns**: 21  
- Key Fields:  
  - **Churn**: Indicates if the customer has left (Yes/No)  
  - **Tenure**: Duration of a customer's association (in months)  
  - **SeniorCitizen**: Binary indicator (0 = No, 1 = Yes)  
  - **InternetService**: Type of internet service (DSL, Fiber optic, None)  
  - **Contract**: Customer contract type (Month-to-month, One year, Two year)  
  - **PaymentMethod**: Mode of payment (Electronic check, Mailed check, etc.)  
  - **MonthlyCharges** & **TotalCharges**: Billing-related information  

---

## Key Findings  
1. **Churn Rate**:  
   - **26.54%** of customers churned.  
   - Senior citizens are **41.7%** more likely to churn compared to non-senior citizens (22.3%).  

2. **Service Usage & Churn**:  
   - Customers with **fiber optic internet** and **multiple lines** have higher churn rates.  
   - **Month-to-month contract holders** make up **85%** of churned customers.  
   - Users paying via **electronic checks** show higher churn compared to automatic payment methods.

3. **Tenure Impact**:  
   - New users (1-2 months of tenure) are most likely to churn.  
   - Long-term customers (55+ months) show a significantly lower churn rate (<15%).

---

## Recommendations  
- **Improve Fiber Optic Services**: Address any performance issues to reduce dissatisfaction.
- **Encourage Long-term Contracts**: Offer incentives to shift users from month-to-month to annual contracts.
- **Promote Automatic Payments**: Provide discounts for adopting automatic payment methods.
- **Engage New Customers**: Focus on enhancing customer satisfaction during the first 3 months.

---


