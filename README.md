# 🛡️ Risk Scoring Dashboard

## 1. Project Title / Headline

**🛡️ Risk Scoring Dashboard**  
An interactive Power BI dashboard designed to analyze customer credit risk, loan exposure, repayment behavior, credit scores, and risk categories to support better lending and risk-management decisions.

---

## 2. Short Description / Purpose

The **Risk Scoring Dashboard** is an interactive Power BI report that provides a complete overview of customer credit risk and loan performance.

It helps users monitor **risk scores, credit scores, loan amounts, outstanding balances, payment delays, missed payments, debt-to-income ratio (DTI), and customer risk categories** through dynamic and easy-to-understand visualizations.

---

## 3. Tech Stack

The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Used to design and develop the interactive dashboard.
* 📂 **Power Query** – Used for data cleaning, transformation, and preparation.
* 🧠 **DAX (Data Analysis Expressions)** – Used to create calculated columns, measures, KPIs, and risk classifications.
* 🔗 **Data Modeling** – Used to organize customer, loan, payment, and risk-related information.
* 📈 **Data Visualization** – Created KPI cards, bar charts, donut charts, tables, slicers, and interactive filters.
* 📁 **File Format** – `.pbix` for Power BI development and `.png` for dashboard screenshots.

---

# 4. Data Source

**Source:** Customer Risk / Loan Risk Dataset

The dataset contains customer and financial risk information, including:

* Customer ID
* Customer Name
* Age
* Gender
* City
* Income
* Credit Score
* Loan Amount
* Outstanding Amount
* Payment Delays
* Missed Payments
* Debt-to-Income Ratio (DTI)
* Employment Status
* Risk Score
* Risk Category / Risk Level
* Suspicious Transactions

The data was cleaned and transformed using **Power Query** before creating DAX calculations and Power BI visualizations.

---

# 5. Features / Highlights

## Business Problem

Financial institutions need to identify customers who may have a higher probability of loan default or repayment problems.

Analyzing customer information manually can make it difficult to identify high-risk customers and monitor important financial indicators.

Key questions include:

* Which customers have the highest risk scores?
* How many customers are high, medium, or low risk?
* Which cities have the highest-risk customers?
* Which employment categories have higher credit risk?
* How does credit score affect customer risk?
* Which customers have high DTI?
* Which customers have multiple payment delays or missed payments?
* What is the total outstanding loan exposure?

---

## Goal of the Dashboard

The dashboard aims to:

* Monitor overall customer risk.
* Identify high-risk customers.
* Analyze credit score patterns.
* Monitor loan and outstanding amounts.
* Analyze payment delays and missed payments.
* Compare risk across cities and employment categories.
* Identify customers requiring further investigation.
* Support data-driven lending and risk-management decisions.

---

# 6. Walkthrough of Key Visuals

## 🏠 Home Page

The Home page provides a high-level summary of the entire risk portfolio.

### KPI Cards

* 👥 **Total Customers**
* 📊 **Average Risk Score**
* 🚨 **High-Risk Customers**
* 💳 **Average Credit Score**

### Visualizations

* Risk Category Distribution
* Average Risk Score by City
* High-Risk Customers by Employment Status
* Customers with Payment Delays by Gender
* Missed Payments by Gender
* Top High-Risk Customers

Interactive slicers can be used for:

* City
* Risk Category
* Gender
* Employment Status

---

# 7. 📊 Risk Overview

The Risk Overview page focuses on identifying and analyzing customer risk.

### KPIs

* Total Customers
* High-Risk Customers
* Average Risk Score
* Average Credit Score
* Average DTI

### Visuals

* Risk Category Distribution
* Risk Score by City
* Risk Score by Employment Status
* Risk Score by Age Group
* Credit Score vs Risk Score
* DTI by Risk Category
* Payment Delays by Risk Category

This page helps management understand **where financial risk is concentrated**.

---

# 8. 👤 Customer Analysis

The Customer Analysis page provides detailed customer-level information.

### Customer Details

* Customer ID
* Customer Name
* Age
* Gender
* City
* Income
* Credit Score
* Loan Amount
* Outstanding Amount
* Payment Delays
* Missed Payments
* DTI
* Risk Score
* Risk Level

### Interactive Filters

* City
* Gender
* Age
* Risk Level
* Employment Status

This allows users to drill down from overall risk to an individual customer.

---

# 9. 💳 Loan / Transaction Analysis

This page focuses on financial exposure and repayment behavior.

### KPIs

* Total Loan Amount
* Total Outstanding Amount
* Average Loan Amount
* Average Outstanding Amount
* Total Missed Payments
* Average DTI

### Visualizations

* Loan Amount by City
* Outstanding Amount by Risk Level
* Loan Amount by Risk Category
* DTI by Risk Category
* Missed Payments by Risk Level
* Credit Score vs Loan Amount

This helps identify customers with **high financial exposure and repayment risk**.

---

# 10. 🚨 Alert / High-Risk Customers

The Alert page identifies customers requiring attention.

### Example Alert Rules

| Condition | Alert |
|---|---|
| Risk Score > 70 | 🔴 High Risk |
| Credit Score < 500 | 🔴 Critical |
| DTI > 50% | 🔴 Critical |
| Missed Payments > 2 | 🔴 Critical |
| Payment Delays > 3 | 🟠 Warning |
| Risk Score 50–70 | 🟠 Medium Risk |

### Alert Table

**Customer ID | Customer Name | Risk Score | Risk Level | Credit Score | DTI | Missed Payments | Loan Amount | Alert Status**

This page allows risk teams to quickly identify customers who may require **further review or intervention**.

---

# 11. Business Impact & Insights

### 🛡️ Risk Management
Identify high-risk customers and prioritize them for further assessment.

### 💳 Credit Assessment
Analyze credit scores, income, DTI, and repayment behavior to understand customer creditworthiness.

### 💰 Loan Exposure
Monitor loan amounts and outstanding balances to understand overall financial exposure.

### 🚨 Early Warning System
Payment delays, missed payments, high DTI, and low credit scores can be used as early warning indicators.

### 📍 Geographic Analysis
Identify cities with higher concentrations of risky customers.

### 👥 Customer Segmentation
Compare risk levels across age, gender, employment status, and other customer characteristics.

### 📈 Business Decision Support
Help financial institutions make more informed decisions regarding **loan approval, customer monitoring, risk mitigation, and collection strategies**.

---

# 12. Screenshots / Demo

The dashboard consists of the following pages:

* 🏠 **Home**
* 📊 **Risk Overview**
* 👤 **Customer Analysis**
* 💳 **Loan / Transaction Analysis**
* 🚨 **Alerts**

---

## 🔥 Short Resume / LinkedIn Version

**Risk Scoring Dashboard | Power BI**

Developed an interactive **Risk Scoring Dashboard using Power BI** to analyze customer credit risk, loan exposure, repayment behavior, and financial indicators. Used **Power Query for data transformation and DAX for calculated measures and risk classification**. Created interactive KPI cards, risk-category analysis, city-wise risk analysis, customer-level risk tables, and high-risk customer alerts. The dashboard enables users to identify high-risk customers, monitor credit scores, DTI, missed payments, and outstanding loans to support data-driven risk-management decisions.
