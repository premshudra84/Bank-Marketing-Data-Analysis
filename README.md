# Bank Marketing Data Analysis & Interactive Dashboard

## 📌 Project Overview

This project analyzes bank marketing data to understand customer characteristics
and patterns related to term-deposit subscription.

The project uses Python for data preparation and exploratory analysis and
Microsoft Power BI to create an interactive dashboard.

---

## 🎯 Project Objectives

- Analyze customer demographic information.
- Understand different marketing contact methods.
- Analyze campaign contact activity.
- Study previous campaign outcomes.
- Calculate the overall subscription rate.
- Create an interactive Power BI dashboard.
- Present important business insights through visualizations.

---

## 📊 Dataset

The cleaned dataset contains:

- Total Customers: **41,176**
- Subscribed Customers: **4,639**
- Subscription Rate: **11.27%**
- Target Variable: `y`
- `y = 1` → Subscribed
- `y = 0` → Not Subscribed

---

## 🧹 Data Cleaning

The dataset was prepared before analysis by:

- Checking the dataset structure.
- Checking missing or problematic values.
- Checking duplicate records.
- Reviewing data types.
- Preparing the target variable for analysis.

---

## 📈 Exploratory Data Analysis

The following areas were analyzed:

- Customer job distribution
- Contact method
- Education
- Marital status
- Average age by subscription status
- Campaign contacts
- Previous campaign outcome
- Subscription status

---

## 📊 Power BI Dashboard

The Power BI dashboard contains two pages.

### Main Dashboard

The Main Dashboard includes:

- Total Customers
- Subscription Rate
- Subscribed Customers
- Subscription Status
- Customers by Contact Method
- Subscription Rate by Campaign Contacts
- Subscription Rate by Previous Campaign Outcome

### Customer Analysis

The Customer Analysis page includes:

- Customers by Job
- Average Age by Subscription Status
- Customers by Marital Status
- Customers by Education

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Microsoft Power BI
- DAX
- Data Cleaning
- Exploratory Data Analysis

---

## 📌 Key Results

| Metric | Result |
|---|---:|
| Total Customers | 41,176 |
| Subscribed Customers | 4,639 |
| Subscription Rate | 11.27% |

---

## 📁 Project Structure

```text
Bank-Marketing-Data-Analysis/
│
├── data/
│   └── bank_marketing_cleaned.csv
│
├── notebook/
│   └── Bank_Marketing_Analysis.ipynb
│
├── powerbi/
│   └── Bank_Marketing_Dashboard.pbix
│
├── report/
│   └── Bank_Marketing_Data_Analysis_Project_Report.docx
│
└── README.md
