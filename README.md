# bank-customer-churn-analysis
# 💳 Bank Customer Churn Prediction

## 📌 Overview Dataset 

This project analyzes customer data to predict churn and identify key factors affecting customer retention.
This dataset analyzes banking customer information to predict the risk of churn (Exited). The goal is to help the bank proactively retain customers by analyzing demographic characteristics and financial behavior.


## 🎯 Objectives
Identify characteristics of customers at high risk of churn. 
Key factors leading to high churn risk. 
Analyze customer segments to develop appropriate intervention strategies.
Solutions for customer retention.
---

## 📊 Dataset Features
- Age
- Gender
- Credit Score
- Balance
- Number of Products
- Estimated Salary

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Power BI
- SQL


## 📊 Dashboard
<img width="1017" height="525" alt="image" src="https://github.com/user-attachments/assets/f16cc916-0bf7-42fa-93af-d9daa74f2205" />

## 📊 Key Insights from Bank Customer Churn Analysis 
<img width="538" height="245" alt="image" src="https://github.com/user-attachments/assets/6b6ac12d-d6fa-44e6-aa96-3e2f29d7e069" />

## 📊 Key Findings from Exploratory Data Analysis (EDA)

### 1. Overall Churn Rate & Customer Profile Comparison
- The overall **churn rate** in the dataset is approximately **20%**.
- Churned customers have an **average account balance 15% higher** than the overall average.
- The average **age** of churned customers is **about 5 years older** than non-churned customers.
- There is **no significant difference** in credit scores between churned and retained customers.

**Conclusion**:  
Churned customers are mainly **older individuals** who maintain relatively high balances in their accounts. This suggests that wealthier, more mature customers are leaving the bank, which represents a significant loss of high-value clients.

---

### 2. Customer Demographics & Churn Patterns

**Age Group Analysis**  
- Younger customers (18–25 and 26–35 years old) are the **least likely to churn**.  
- Older age groups (46–55 and 56–65) show significantly higher churn rates, with the highest churn rate reaching **50%** in certain older segments.

**Credit Score Analysis**  
- There is a clear negative correlation: **the higher the credit score, the lower the churn rate**.  
- Customers with low credit scores (300–499) have the highest churn rate at **57.6%**.

**Conclusion**:  
Younger customers with higher credit scores tend to be more loyal to the bank. **Age** appears to be one of the most significant factors influencing customer churn.

![Age Group Churn](https://github.com/user-attachments/assets/c62b518f-f31f-4eac-ab3b-b506f93c5fca)  
![Credit Score Churn](https://github.com/user-attachments/assets/16bcc984-fa17-43c4-a7b9-74575373d1c3)

---

### 3. Geographic Analysis: France, Germany, and Spain
The dataset covers customers from three countries: **France**, **Germany**, and **Spain**.

- **Germany** has the **highest overall churn rate** among the three countries.  
- It also records the highest churn rates for both **male** and **female** customers separately.  
- However, Germany simultaneously has the **highest average account balance**, indicating that the bank is losing a large number of high-value, high-balance customers in this market.

**Conclusion**:  
The German customer segment represents a high-potential but high-risk group. The elevated churn rate, despite high balances, suggests strong competition from other banks offering better products, rates, or services. The bank needs to develop more targeted retention strategies specifically for the German market to protect and grow this valuable customer base.

![Geography Churn](https://github.com/user-attachments/assets/06231480-93d2-472d-8924-274e9d3c800a)

---

### 4. High-Risk Customer Segments & Recommended Actions

**High-Risk Groups Identified:**

- **Group 1: Customers with only 1 product**  
  This group accounts for nearly **50% of total customers**. With minimal connection to the bank, they are quick to switch when a better offer appears elsewhere.

- **Group 2: Customers over 55 years old**  
  Mostly retired individuals with substantial savings who do not need loans. They tend to switch banks for better benefits, convenience, and services tailored for seniors.

- **Group 3: Customers with credit score below 500**  
  This high-risk lending segment consists largely of young people. Despite making up a large portion of the customer base, they face difficulties getting loan approvals, leading to low satisfaction and high churn.

**Recommended Solutions:**

- **For customers with only 1 product**:  
  Implement aggressive cross-selling strategies. Offering additional products (credit cards, savings accounts, insurance, investments) will increase customer engagement, create stronger attachment, and significantly reduce churn while boosting revenue.

- **For customers with low credit scores**:  
  Although currently high-risk, this group (mostly young customers) has high consumption needs and strong long-term potential. Developing tailored products such as beginner-friendly credit cards, micro-loans, or digital banking features could help build loyalty and convert them into long-term profitable customers.

---
