
![image](https://github.com/user-attachments/assets/7d1f1cd9-3273-4972-b641-d5ac5a0c3e46)

# Project Title: Customer Retetion Dashboard - Kiwibank | Power BI



Author: [Olivia Nguyen]  
Date: April 2025  
Tools Used: Power BI 

---

## 📑 Table of Contents  
I. [📌 Background & Overview](#-background--overview)  
II.[📊 Power BI Visualization](#-power-bi-visualization)  
III. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)  
IV. [📂 Dataset Description](#-dataset-description)  


## 📌 Background & Overview

### 📖 What is this project about?
This Power BI project analyzes customer churn for a New Zealand bank, focusing on demographics like age, activity status, credit card ownership, and geographic location, alongside financial metrics such as account balance and tenure. It incorporates advanced visualizations, including column-in-column charts, and employs machine learning to identify key churn drivers, providing actionable insights for customer retention strategies.


### 👤 Who is this project for?   
This project is designed for stakeholders within the banking and financial services sector, particularly those operating in the New Zealand market. It serves professionals such as customer experience managers, marketing analysts, data scientists, and business strategists who aim to understand and reduce customer churn.  

### ❓ Business Questions:
- Which demographic factors (e.g., age, activity status, credit card ownership) are most associated with customer churn?  
- How does geographic location within New Zealand influence churn rates?  
- What financial metrics (e.g., account balance, tenure) correlate with higher or lower churn?  
   
## 📊 Power BI Visualization

### Dashboard 1 Preview
![image](https://github.com/user-attachments/assets/979aadd6-698b-4f94-b48a-fabac0264c51)


### Dashboard 2 Preview

![image](https://github.com/user-attachments/assets/845ada29-f7f7-4131-941b-bc6bcf583324)


## 🔎 Final Conclusion & Recommendations 

 **Key Insights:**
- Low-income males (18–45) have the lowest churn – a core retention segment.
- Female customers and Palmerston North residents show higher churn.
- 3–4 product users face the highest churn risk.
- Very high-income and very high-balance customers require tailored retention.
- Good credit = lowest churn; excellent credit = high-value targets.
- Inactive users (48%) churn at 2x the rate of active users.

**Recommendations:**
- Reward loyalty for females and excellent credit customers.
- Offer bundles to 3–4 product holders.
- Tailor messaging for income and balance extremes.
- Re-engage inactive users with targeted campaigns.
- Focus retention efforts on the 18–45 age group and high-churn regions.

By acting on these insights, the business can reduce churn, boost engagement, and strengthen customer loyalty across key segments.

## 📂 Dataset Description

### 🌐 Data Source
- The Customer Churn dataset originates from Kaggle and can be accessed at: https://www.kaggle.com/datasets/smmmmmmmmmmmm/customer-churn-analysis-of-kiwibank/data  
- Size: 10,00 rows, 13 columns
- Format: .csv

### 🔀 Table schema
<details>
<summary>Table: Customer Churn of Kiwibank </summary>  

| Number | Variable name       | Definition                                                | Data Type |
| ------ | ------------------- | --------------------------------------------------------- | --------- |
| 1      | Customer_id         | Unique identifier for each customer                       | Number    |
| 2      | Surname             | Surname of the customer                                   | Text      |
| 3      | CreditScore         | Customer’s creditworthiness                               | Number    |
| 4      | Geography           | City of the customer                                      | Text      |
| 5      | Gender              | Gender of customer                                        | Text      |
| 6      | Age                 | Age of the custome                                        | Number    |
| 7      | Tenure              | Tenure of customer in organization                        | Number    |
| 8      | Balance             | Customers' balance account                                | Number    |
| 9      | NumberOfProducts    | How many different products a customer holds              | Number    |
| 10     | Has Credit Card     | Whether a customer owns a credit card                     | Number    |
| 11     | Is Active Member    | Indicates if the customer is currently active             | Number    |
| 12     | Estimated Salary    | Annual income of the customer                             | Number    |
| 13     | Churn               | Churn Flag                                                | Number    |

</details>


