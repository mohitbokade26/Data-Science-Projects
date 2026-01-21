# 🏦 Financial Risk Analysis with Python
Customer Transaction & Risk Analytics

![Language](https://img.shields.io/badge/Language-Python-blue)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%20%7C%20NumPy-green)
![Domain](https://img.shields.io/badge/Domain-Financial%20Analytics-orange)
![Focus](https://img.shields.io/badge/Focus-Risk%20Analysis-red)
![Level](https://img.shields.io/badge/Level-Intermediate-purple)

---

## 📌 Project Overview

This project involves a detailed analysis of customer financial transaction data to evaluate
spending patterns, account activity, and potential financial risks.

Using Python-based data analysis and statistical techniques, the project identifies
high-risk transaction behavior, balance instability, and customer segments that require
enhanced monitoring. The analysis supports proactive financial risk assessment and
data-driven decision-making.

---

## 🎯 Business Objectives

- Analyze customer transaction behavior across different account types  
- Identify patterns associated with financial risk and balance instability  
- Segment customers based on activity levels and balance trends  
- Detect anomalies and irregular transaction behavior  
- Support data-driven risk assessment and decision-making  

---

## 🔧 Tools & Skills Used

- Python  
- Pandas & NumPy  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Statistical Analysis & Hypothesis Testing  
- Risk Segmentation & Anomaly Detection  
- Data Visualization
---

## 📂 Dataset Description

The dataset consists of transaction-level financial data, including:

- Customer and account identifiers  
- Account types (Savings, Current, Credit, Loan)  
- Transaction types (Deposit, Withdrawal, Transfer, Payment)  
- Transaction amounts and account balances  
- Risk scores and credit ratings  
- Transaction dates and account tenure  

This dataset enables both descriptive analysis and financial risk evaluation.

---

## 🔍 Methodology

### 🧹 1. Data Cleaning & Preparation
- Converted transaction dates into proper datetime format  
- Removed duplicate records  
- Ensured numerical consistency for financial fields  
- Standardized account and transaction categories  

---

### 📊 2. Descriptive Transaction Analysis
- Calculated monthly and yearly totals of:
  - Credit transactions  
  - Debit transactions  
  - Net transaction volume  
- Analyzed credit vs debit trends over time  
- Identified top-performing and bottom-performing accounts  
- Flagged dormant accounts using transaction gaps (≥ 60 days)  

---

### 👤 3. Customer Profiling & Segmentation
- Grouped accounts based on transaction frequency:
  - High activity  
  - Medium activity  
  - Low activity  
- Segmented customers using:
  - Average account balance  
  - Transaction volume  
- Created profiles for:
  - High net inflow accounts  
  - High-frequency, low-balance accounts  
  - Negative or near-zero balance accounts  

---

### ⚠️ 4. Financial Risk Identification
- Identified large debit transactions using threshold analysis  
- Detected overdraft accounts with negative balances  
- Measured balance volatility using standard deviation  
- Classified accounts into volatility risk levels  
- Detected anomalies using Z-score analysis  
- Identified suspicious customers based on risk score and behavior  

---

### 📈 5. Data Visualization
- Credit vs debit transaction trends  
- Large debit transaction distribution  
- Overdraft vs non-overdraft account analysis  
- Balance volatility distribution  
- Z-score based anomaly detection plots  
- Risk score comparison visuals  

---

### 🧪 6. Hypothesis Testing
- Conducted Z-test to evaluate:
  - Whether high transaction volume accounts have higher average balances than low-volume accounts  

**Result:**  
- No statistically significant difference found  
- Transaction frequency alone is not a reliable indicator of financial stability  

---

## 📊 Key Insights

- Debit transactions consistently exceed credit transactions, indicating higher spending behavior  
- Large debit transactions and overdrafts are strong indicators of financial risk  
- High transaction frequency does not necessarily imply financial stability  
- Balance volatility significantly increases risk exposure  
- Dormant accounts indicate low customer engagement  
- Anomalous transactions are relatively rare but critical to monitor  
- Suspicious behavior is distributed across multiple customer segments  

---

## 💡 Recommendations

- Closely monitor accounts with frequent large debit transactions  
- Implement real-time alerts for overdrafts and low account balances  
- Track high-volatility accounts for early risk detection  
- Combine multiple risk indicators for accurate risk profiling  
- Re-engage dormant customers through targeted communication  
- Educate high-spending customers on balance management and savings practices  
- Use continuous monitoring instead of one-time analysis  

---

## 📌 Business Impact

- Improves early detection of financial risk  
- Reduces potential losses due to overdrafts and irregular transactions  
- Enhances customer monitoring and segmentation  
- Strengthens data-driven risk management strategies  
- Supports informed financial decision-making  

---
## 📁 Files in This Folder

- `goldman_sachs.csv`  
  Contains the raw transaction-level dataset used for financial risk analysis, including
  transaction amounts, account balances, risk scores, and time-based information.
  
- Goldman_Sachs_Financial_Risk_Analysis.ipynb file

- ---

## 🏁 Conclusion

This project demonstrates how **Python-based data analysis** can be used to assess **financial risk** by analyzing customer transaction behavior, balance trends, and account activity.

By identifying **high-risk patterns, anomalies, and unstable balance behavior**, the analysis supports **proactive risk management** and enables **data-driven financial decision-making**.  

---

## 👤 Author

**Mohit Bokade**  
Aspiring Data Analyst | Python | Pandas | NumPy | Financial Analytics  

🔗 **GitHub:** https://github.com/mohitbokade26

 

 


