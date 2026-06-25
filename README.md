
# Telco Customer Churn Analysis Dashboard | Power BI

##  Project Overview
Customer churn is one of the biggest challenges faced by telecommunications companies. Acquiring a new customer is significantly more expensive than retaining an existing one, making customer retention a critical business objective.

This project analyzes customer behavior using the Telco Customer Churn Dataset from Kaggle and presents an interactive Power BI dashboard that identifies the major factors contributing to churn. The dashboard enables business stakeholders to monitor churn trends, understand customer behavior, quantify revenue loss, and develop targeted retention strategies.


---
## Business Problem 
Telecommunication companies lose substantial recurring revenue when customers discontinue their services. Understanding **who is leaving, why they are leaving, and what business actions can reduce churn** is essential for improving customer retention and maximizing customer lifetime value.

This project addresses the following business questions:

Which customers are most likely to churn?
Which customer characteristics influence churn?
Which services contribute to customer retention?
How much revenue is lost because of churn?
What actions can reduce future churn?

---
## Project Objectives

- Analyze customer demographics and subscription behavior.
- Identify high-risk customer segments.
- Measure revenue loss caused by customer churn.
- Evaluate how contracts, payment methods, tenure, and services influence churn.
- Provide actionable recommendations for improving customer retention.

--- 

## 🛠️ Tools & Technologies
- **Dataset**: [Telco Customer Churn – Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Tool**: Power BI Desktop
- **Data Cleaning**: Power Query
- **Analysis Logic**: DAX (Data Analysis Expressions)
- **Visualization Types**: Cards, Donut Charts, Bar Charts, Line Charts, Matrix, and Waterfall Charts

---
## Data Preparation

Data preprocessing was performed using Power Query before loading the dataset into Power BI.

The cleaning process included:
- Removing unnecessary columns
- Verifying data types
- Handling missing values
- Standardizing categorical values
- Preparing fields for analysis
- Creating tenure groups for customer segmentation


---
## Dashboard Overview

### 🟠 **Customer Overview Dashboard**
<img width="1141" height="655" alt="image" src="https://github.com/user-attachments/assets/ab844fbf-bd1f-4fea-ae2c-a7a1ea922be2" />

This dashboard provides a high-level overview of customer churn by analyzing demographics, subscription behavior, contracts, payment methods, and internet services.

#### **KPIs**
| Metric | Description | Value |
|--------|--------------|-------|
| **Customers at Risk** | Total churned customers | **1,869** |
| **Average Tenure** | Mean customer tenure | **32.37 months (~2.7 years)** |
| **Yearly Charges** | Total annual charges | **$16.06M** |
| **Annual Charges Lost** | Yearly churn-related loss | **$1.67M** |
| **Direct Revenue Loss** | Immediate revenue loss | **$0.14M** |

#### **Visual Insights**
 ##### Customer Demographics

1. **Senior Citizens**
- Approximately **42%** of churned customers are senior citizens, making this demographic one of the highest-risk customer groups.

 **Business Insight**
-Senior customers may require simpler plans, improved customer support, or better onboarding experiences.

2. **Dependents**
- Only **6.5%** of churned customers have dependents.

**Business Insight**
- Customers with family members tend to remain subscribed longer because switching providers affects multiple users.

3. **Gender**
- Customer churn is distributed almost equally across male and female customers.

**Business Insight**
- Gender does not appear to be a strong predictor of churn.

---
 ##### Customer Tenure
- The majority of churn occurs during the customer's **first year.**
- Churn steadily decreases as customer tenure increases.

**Business Insight**
- The onboarding experience is one of the most important stages in the customer lifecycle.
- Improving customer engagement during the first 6–12 months can significantly reduce churn.

---
 ##### Payment Methods
- Electronic Check users represent the largest proportion of churned customers.

**Business Insight**
- Manual payment methods often indicate lower customer commitment compared to automatic payment options such as bank transfer or credit card auto-pay.
- Encouraging customers to adopt automatic payments may improve retention.

---
 ##### Contract Types
- Month-to-Month contracts account for approximately 55% of all churned customers.
- Customers with one-year and two-year contracts exhibit significantly lower churn.

**Business Insight**
- Long-term contracts increase customer commitment and reduce the likelihood of switching providers.

---
 ##### Internet Service
 - Fiber Optic customers experience the highest churn.
   
| **Internet Service**	| **Churn Share** |
|----------------------|-----------------|
| Fiber Optic	      | 43.9%       |
| DSL	              | 34.3%       |
| No Internet	      | 21.6%       |

**Business Insight**
Higher churn among Fiber Optic customers may indicate pricing concerns, service quality issues, or higher customer expectations that require further investigation.

---

### 🟣 **Deep-Dive Dashboard**
<img width="1162" height="655" alt="image" src="https://github.com/user-attachments/assets/1dd1a65c-d2a9-430a-9ee4-cd851e59ed8a" />

The second dashboard focuses on understanding the behavioral patterns behind customer churn and identifying revenue protection opportunities.

#### **Visual Insights**
1. **Revenue Loss by Payment Method (Waterfall Chart):**  
 - A Waterfall Chart illustrates the contribution of each payment method to total revenue loss.
 - Electronic Check customers contribute the highest revenue loss.

**Business Insight**
- Reducing churn among Electronic Check users would provide the greatest financial benefit.
---

2. **Churn by Number of Services (Bar Chart):**  
- Customers subscribed to 2–3 services experience the highest churn.
- Customers using 6 or more services exhibit the lowest churn.

**Business Insight**
- Customers with multiple products become more engaged with the company's ecosystem, making them less likely to switch providers.
- Cross-selling additional services can improve retention.

---

3. **Churn Count by Risk Segment (Bar Chart):**  
- Medium-risk customers account for the highest number of churn cases.

**Business Insight**
- Retention campaigns often focus only on high-risk customers, while medium-risk customers represent a significant opportunity for proactive intervention.

---

4. **Churn Rate by Tenure (Line Area Chart):**
- Customer churn peaks around 2–3 years before gradually declining.

**Business Insight**
- Customers often reconsider their service provider after remaining with the company for several years. Loyalty rewards and contract renewal campaigns can improve retention during this stage.

---

5. **Churn by Service Combination (Matrix):**
- Customers without **Online Security** or **Online Backup** services demonstrate higher churn.
- Customers subscribed to these services remain more loyal.

**Business Insight**
- Bundling value-added services increases customer engagement and strengthens long-term retention.

---

6. **Churn Count by Contract (Bar Chart):**
- The deep-dive dashboard confirms that Month-to-Month customers continue to represent the largest share of churn.
- This reinforces the findings from the overview dashboard.

---

#### **Business Insights**  

- Customer churn is highest during the first year of subscription.
- Senior citizens represent the highest-risk demographic segment.
- Month-to-Month contracts experience substantially higher churn than long-term contracts.
- Electronic Check customers contribute the greatest revenue loss.
- Fiber Optic users exhibit the highest churn among internet service types.
- Customers using multiple services demonstrate stronger retention.
- Online Security and Online Backup services are associated with lower churn rates.
- Approximately **$1.67 million** in annual revenue is at risk due to customer churn.


---

####  **Business Recommendations**

1. **Improve Customer Onboarding**
- Develop onboarding programs during the first year to increase customer satisfaction and reduce early churn.

2. **Encourage Long-Term Contracts**
- Offer discounts, loyalty rewards, or bundled benefits for customers upgrading to annual contracts.

3. **Promote Automatic Payments**
- Encourage Electronic Check users to adopt AutoPay or digital payment methods through incentives.

4. **Improve Fiber Optic Experience**
- Investigate customer feedback related to pricing, service quality, and technical support for Fiber Optic users.

5. **Expand Cross-Selling**
- Bundle Online Security, Online Backup, Device Protection, and Streaming services to increase customer engagement.

6. **Target Medium-Risk Customers**
- Launch personalized retention campaigns before medium-risk customers transition into high-risk segments.

---
## Project Outcome

This dashboard transforms raw customer data into actionable business intelligence.

The analysis highlights that **customer tenure, contract type, payment method, internet service, and service adoption are the strongest indicators of churn.**

By implementing targeted retention strategies based on these insights, a telecom company can improve customer loyalty, reduce revenue loss, and make more informed business decisions.



---

