# 📊 Customer Churn Analysis

## 📌 Project Overview

Customer churn is an important business problem for subscription-based companies because losing existing customers can directly affect revenue and growth.

This project analyzes customer data from a telecommunications company to identify the major factors associated with customer churn.

The analysis focuses on customer demographics, services, contracts, payment methods, tenure, monthly charges, and support-related services to understand which customer groups are more likely to leave.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze the overall customer churn rate.
- Identify customer segments with higher churn.
- Study the relationship between tenure and churn.
- Analyze the impact of contract type on churn.
- Examine monthly charges and customer churn.
- Analyze internet services and payment methods.
- Study the effect of Tech Support and Online Security.
- Analyze Partner and Dependents status.
- Identify important business insights.
- Provide recommendations that may help improve customer retention.

---

## 📂 Dataset

The project uses the *Telco Customer Churn Dataset*.

The dataset contains *7,043 customer records* and *21 columns*.

Important features include:

- customerID
- gender
- SeniorCitizen
- Partner
- Dependents
- tenure
- PhoneService
- MultipleLines
- InternetService
- OnlineSecurity
- OnlineBackup
- DeviceProtection
- TechSupport
- StreamingTV
- StreamingMovies
- Contract
- PaperlessBilling
- PaymentMethod
- MonthlyCharges
- TotalCharges
- Churn

The target variable for the analysis is *Churn*.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Visual Studio Code
- Git
- GitHub

---

## 🧹 Data Cleaning

Before performing exploratory data analysis, the dataset was cleaned and prepared.

The major steps included:

- Inspecting dataset structure and data types.
- Checking for missing values.
- Converting TotalCharges to a numeric data type.
- Handling missing or invalid values.
- Checking duplicate records.
- Verifying the dataset after cleaning.

---

## 📊 Exploratory Data Analysis

The analysis investigates several factors that may influence customer churn.

### 1. Overall Churn Distribution
Analyzed the proportion of customers who stayed versus customers who churned.

### 2. Contract Type
Compared churn rates across:

- Month-to-month
- One-year
- Two-year contracts

### 3. Customer Tenure
Analyzed whether newer or long-term customers are more likely to churn.

### 4. Monthly Charges
Compared the average monthly charges of churned and retained customers.

### 5. Internet Service
Compared churn behavior among customers using:

- DSL
- Fiber optic
- No internet service

### 6. Payment Method
Analyzed churn rates across different payment methods.

### 7. Tech Support
Examined whether customers with Tech Support have lower churn rates.

### 8. Online Security
Analyzed the relationship between Online Security and customer churn.

### 9. Partner Status
Compared churn rates for customers with and without partners.

### 10. Dependents
Examined whether having dependents is associated with customer retention.

### 11. Paperless Billing
Compared churn rates between customers using and not using paperless billing.

### 12. Device Protection
Analyzed whether Device Protection is associated with lower churn.

---

## 💡 Key Business Insights

The analysis identified several important patterns:

- The overall customer churn rate is approximately *26.6%*.
- Customers on *month-to-month contracts* have a substantially higher churn rate than customers with longer-term contracts.
- *Two-year contract customers* show the lowest churn rate.
- Customers with *short tenure* are considerably more likely to churn.
- Churned customers tend to have *higher average monthly charges*.
- *Fiber optic customers* show comparatively high churn.
- Customers using *Electronic Check* have a higher churn rate than several other payment groups.
- Customers without *Tech Support* show higher churn.
- Customers without *Online Security* show higher churn.
- Customers without partners or dependents show comparatively higher churn.
- Customers using *Paperless Billing* show higher churn.
- Customers without *Device Protection* also demonstrate higher churn.

---

## 💼 Business Recommendations

Based on the analysis, the company could consider the following actions:

1. Encourage month-to-month customers to move toward longer-term contracts through discounts or loyalty benefits.

2. Focus retention campaigns on customers during their first few months of service.

3. Investigate customer experience and pricing for Fiber Optic plans.

4. Promote Tech Support, Online Security, and Device Protection services where they provide customer value.

5. Review customers with high monthly charges and provide suitable plans or personalized offers.

6. Target high-risk customer segments with proactive retention campaigns before they churn.

7. Investigate the high churn associated with Electronic Check users and improve the payment experience where necessary.

---

## 📁 Project Structure

```text
Customer-Churn-Analysis/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── customer_churn_analysis.ipynb
│
├── README.md
│
└── requirements.txt

## 🚀 How to Run the Project

Clone the repository:
git clone <repository-url>
Install the required libraries:
pip install -r requirements.txt
Then open:
notebooks/customer_churn_analysis.ipynb
Run the notebook cells from top to bottom.

## 📈 Conclusion

The analysis indicates that customer churn is strongly associated with contract type, tenure, monthly charges, internet service, payment method, and access to support-related services.
Customers with short tenure, month-to-month contracts, higher monthly charges, and limited support services represent important high-risk segments.
These findings can help a telecommunications company design more targeted retention strategies and make data-driven decisions to reduce customer churn.


## 👤 Author

*Amritpal Singh*

*Data Analyst | Business Analyst*

### Skills Demonstrated

Python • Pandas • NumPy • Matplotlib • EDA • Data Cleaning • Data Visualization • Business Analysis