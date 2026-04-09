# bank-customer-churn-analysis
# 💳 Bank Customer Churn Prediction

## 📌 Overview
This project analyzes customer data to predict churn and identify key factors affecting customer retention.

---

## 🎯 Objectives
- Identify factors influencing customer churn
- Build a prediction model
- Provide business insights to reduce churn

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
- Scikit-learn (Logistic Regression)
- Power BI
- SQL

---

## 📈 Key Insights
- Customers with low balance are more likely to churn
- Fewer products → higher churn risk
- Credit score impacts retention

---

## 🤖 Model
- Logistic Regression
- Evaluated using accuracy & confusion matrix

---

## 📊 Dashboard
<img width="1117" height="625" alt="image" src="https://github.com/user-attachments/assets/f16cc916-0bf7-42fa-93af-d9daa74f2205" />

## 📊 Key Insights from Bank Customer Churn Analysis 

### 1. The Cost of Churn in Banking is Extremely High
- Acquiring a new customer is **5–25 times more expensive** than retaining an existing one.
- Even a small reduction in churn (e.g., 5%) can increase bank profits by **25–95%**.
- In 2025, the **global average churn rate** for traditional retail banks was approximately **15–20%**, while digital-only banks achieved significantly lower churn at around **10.8%**.
- Overall customer retention rate in banking hovered around **75–82%**, meaning banks lose 1 in every 5–6 customers annually on average.

### 2. Overall Churn Rate & Distribution Patterns
- In typical bank datasets (e.g., 10,000 customers), the churn rate often ranges from **19.6% to 20.4%** — roughly 1 in 5 customers leave the bank.
- Churn is **not evenly distributed**. Certain customer segments show dramatically higher risk:
  - **Inactive members** churn at **26.9%**, compared to only **14.3%** for active members (1.9× higher likelihood of leaving).
  - Customers aged **50–59** exhibit the highest churn rate (~56%), even though they represent a smaller portion of the base. They can account for nearly **24% of total churn**.
  - The most vulnerable group: **Inactive customers aged 60–69**, with churn rates sometimes exceeding **90%**.

### 3. Top Drivers of Customer Churn (Feature Importance)
Based on multiple machine learning analyses (including SHAP values, Random Forest, XGBoost, and CatBoost):

- **IsActiveMember** — The strongest predictor. Inactive customers are far more likely to churn.
- **Balance** — Shows a strong non-linear relationship. Customers with very high or very low balances tend to leave more often.
- **Number of Products** — Customers using fewer banking products (e.g., only 1–2) have higher churn risk.
- **Age** — Middle-aged and older segments (especially 40–60) show elevated churn.
- **Geography** — Significant variation by country/region. In European datasets, Germany and France often show higher churn than Spain.
- Other notable factors: Estimated Salary, Credit Score, Tenure, and having a Credit Card (customers without cards sometimes churn more).

Models such as **CatBoost**, **XGBoost**, **LightGBM**, and **Random Forest** consistently achieve high performance (accuracy 87–96%, AUC 0.90–0.96), especially when handling class imbalance with techniques like ADASYN + Tomek Links.

### 4. Business & Strategic Implications
- **Proactive retention is more effective than reactive campaigns**. Predicting churn 2–4 weeks in advance using behavioral signals (transaction activity, inactivity periods, sentiment shifts) allows banks to intervene early.
- **Digital experience matters**: Poor onboarding, lack of personalization, and outdated mobile apps are major churn drivers. Banks investing in AI-powered personalization and seamless omnichannel support see 3.2× faster growth and significantly better retention.
- **Segment-specific strategies work best**:
  - Re-engage inactive customers with targeted offers and reminders.
  - Offer more products/cross-selling to low-product users.
  - Provide premium support and loyalty benefits to high-balance, middle-aged customers.
- In Vietnam and emerging markets, churn is influenced by competition from fintechs, digital banking adoption, and customer expectations for fast, personalized services.

### 5. Key Takeaways & Recommendations
- Churn is preventable when banks shift from lagging metrics (monthly churn rate) to **predictive, explainable AI models**.
- The highest ROI comes from focusing on **high-risk segments** (inactive, older, low-product users) rather than blanket retention campaigns.
- Combining **technical features** (balance, activity, products) with **behavioral and experiential data** (customer support interactions, app usage, sentiment) delivers the most accurate predictions.
- Future focus (2026+): Integrate AI agents for real-time intervention, personalized offers, and proactive loyalty programs to turn “lazy loyalists” into true advocates.


