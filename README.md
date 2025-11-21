
# 📊 Telco Customer Churn Analysis Dashboard

## 🧩 Project Overview
Customer churn is one of the most pressing challenges in the telecom industry, directly impacting revenue and customer lifetime value.  
This project analyzes the **Telco Customer Churn dataset (Kaggle)** using **Power BI** to uncover the key reasons behind churn and propose data-driven retention strategies.

The Power BI dashboard is divided into **two analytical pages**:
1. **Customer Overview Dashboard** – Who is churning and why?  
2. **Deep-Dive Dashboard** – What services, contracts, and behaviors influence churn the most?

---

## 🛠️ Tools & Technologies
- **Dataset**: [Telco Customer Churn – Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Tool**: Power BI Desktop
- **Data Cleaning**: Power Query
- **Analysis Logic**: DAX (Data Analysis Expressions)
- **Visualization Types**: Cards, Donut Charts, Bar Charts, Line Charts, Matrix, and Waterfall Charts

---


## 📊 Dashboard Overview

### 🟠 **Customer Overview Dashboard**
<img width="1141" height="655" alt="image" src="https://github.com/user-attachments/assets/ab844fbf-bd1f-4fea-ae2c-a7a1ea922be2" />

#### **KPIs**
| Metric | Description | Value |
|--------|--------------|-------|
| **Customers at Risk** | Total churned customers | **1,869** |
| **Average Tenure** | Mean customer tenure | **32.37 months (~2.7 years)** |
| **Yearly Charges** | Total annual charges | **$16.06M** |
| **Annual Charges Lost** | Yearly churn-related loss | **$1.67M** |
| **Direct Revenue Loss** | Immediate revenue loss | **$0.14M** |

#### **Visual Insights**
- **Demographics**:  
  - 42% of churned customers are **Senior Citizens** (most vulnerable group).  
  - Only 6.5% of churned customers have **Dependents** → family plans reduce churn.  
  - Churn is **evenly distributed by gender**.  

- **Tenure (Subscription Time)**:  
  - Majority of churn happens within the **first year (<1 year)**.  
  - Churn steadily decreases as tenure increases.  

- **Payment & Billing**:  
  - **Electronic Check** users make up **33.6%** of churners — highest risk payment method.  
  - **Paperless billing users (59%)** churn more, possibly due to digital-first behavior.  

- **Contract Type**:  
  - **55% of churn** comes from **Month-to-Month contracts**.  
  - Customers with **1-year or 2-year contracts** churn less → stronger customer retention.  

- **Internet Service Type**:  
  - **Fiber Optic** users churn the most (**43.9%**).  
  - **DSL users** show moderate churn (**34.3%**).  
  - **No internet service** users have the lowest churn (**21.6%**).  

#### 🧠 **Key Insights**
1. **Early churn** is the biggest issue — most customers leave within the **first year**.  
2. **Senior citizens** are a high-risk demographic.  
3. **Electronic check** and **month-to-month contract holders** dominate churn.  
4. **Fiber optic users** show higher dissatisfaction or price sensitivity.  
5. **Dependents reduce churn** – family accounts are more loyal.  

#### 💡 **Recommendations**
- **Early Retention:** Create onboarding and loyalty programs for customers in their first 6–12 months.  
- **Target Senior Citizens:** Offer simplified plans and priority support.  
- **Payment Incentives:** Encourage auto-pay and digital payments instead of electronic checks.  
- **Contract Renewal Offers:** Provide discounts for customers switching to yearly contracts.  
- **Service Quality Check:** Investigate Fiber Optic service issues or pricing dissatisfaction.  

---

### 🟣 **Deep-Dive Dashboard**
<img width="1162" height="655" alt="image" src="https://github.com/user-attachments/assets/1dd1a65c-d2a9-430a-9ee4-cd851e59ed8a" />

#### **Visual Insights**
- **Revenue Loss by Payment Method (Waterfall Chart):**  
  - **Electronic check** causes the largest revenue loss (~$84K).  
  - **Mailed check** and **credit card** contribute smaller amounts.  

- **Churn by Number of Services (Bar Chart):**  
  - Customers with **2–3 services (38%)** churn the most.  
  - Customers with **6+ services (20%)** churn the least → more engaged, higher retention.  

- **Churn Count by Risk Segment (Bar Chart):**  
  - **Medium-risk** customers represent the highest churn count.  
  - **High-risk** and **low-risk** customers show similar churn volumes.  

- **Churn Rate by Tenure (Line Area Chart):**  
  - Churn peaks around **2–3 years**, then gradually decreases after **4+ years**.  

- **Churn by Service Combination (Matrix):**  
  - Customers **without Online Security or Backup** churn more.  
  - Those with both services retained better.  

- **Churn Count by Contract (Bar Chart):**  
  - Confirms that **Month-to-Month** contracts dominate churn count.  

#### 🧠 **Key Insights**
1. **Revenue concentration risk:** Most churn-related revenue loss comes from **Electronic check** users.  
2. **Service engagement:** Customers with **multiple add-on services** are less likely to churn.  
3. **Churn peaks around 2–3 years** tenure — need for mid-lifecycle engagement.  
4. **Medium-risk customers** make up the bulk of churn → an overlooked retention opportunity.  
5. **Security/Backup add-ons** improve loyalty → cross-selling can reduce churn.  

#### 💡 **Recommendations**
- **Payment Strategy:** Encourage safe auto-pay methods to reduce electronic check dependency.  
- **Customer Lifecycle Management:** Focus engagement around **2–3 years tenure** with renewal rewards or upgrade offers.  
- **Cross-Selling:** Bundle **Online Security and Backup** services for better retention.  
- **Medium-Risk Focus:** Target personalized campaigns to medium-risk segments before they escalate.  
- **Revenue Protection:** Identify top revenue customers at churn risk and offer retention incentives.  

---

## 📈 Combined Key Insights
| Theme | Key Insight | Impact |
|--------|--------------|--------|
| **Tenure** | Highest churn <1 year; spikes again around 2–3 years | Early-stage onboarding and mid-term re-engagement required |
| **Demographics** | Senior citizens churn the most | Require dedicated plans/support |
| **Payment** | Electronic check users are most churn-prone | Move users to secure auto-pay methods |
| **Contracts** | Month-to-month has 55% churn rate | Push long-term contracts with incentives |
| **Internet Type** | Fiber optic users churn most | Evaluate pricing and service satisfaction |
| **Add-On Services** | Security/Backup add-ons reduce churn | Promote bundled plans |
| **Revenue Loss** | $1.67M lost annually | Prioritize high-value churn prevention |

---

## 💡 Overall Recommendations
1. **Enhance Onboarding:** Focus on customer experience in the first 6 months.
2. **Build Loyalty:** Reward tenure with discounts or free upgrades.
3. **Contract Optimization:** Convert short-term to long-term contracts with incentive programs.
4. **Improve Service Quality:** Especially for fiber optic customers.
5. **Digital Retention:** Create tailored digital loyalty campaigns for paperless billing users.
6. **Mid-Term Engagement:** Offer personalized offers to 2–3 year customers.
7. **Cross-Sell Add-Ons:** Promote Online Security and Backup services to stabilize accounts.


---

## 🏁 Conclusion
The **Telco Customer Churn Dashboard** provides a comprehensive view of customer behavior, revealing that **contract type, tenure, payment method, and service engagement** are the strongest predictors of churn.  
By implementing targeted strategies based on these insights, telecom companies can significantly reduce churn and protect an estimated **$1.67M in annual revenue**.

---

