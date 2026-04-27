# Credit Risk Analysis (EDA)
This project performs an Exploratory Data Analysis (EDA) on customer financial data to identify key factors influencing credit score and overall credit risk.

---

# Project Overview
- Dataset Size: 100,000+ customer records
- Features: Income, loans, payment delays, credit utilization, debt, payment behavior, etc.
- Target Variable: Credit_Score (Good / Standard / Poor)
- Objective: Understand the key drivers of creditworthiness and risk

  ---

# Data Cleaning & Preparation
- Removed irrelevant columns: ID, Customer_ID, Name, SSN
- Handled hidden missing values:
- "NM", "No Data", "Not Specified" → converted to NaN
- Cleaned complex data:
- Extracted Loan_Count from Type_of_Loan
- Standardized column formats and naming
- Ensured dataset consistency and usability

---

# Exploratory Data Analysis
The analysis includes 8 key visualizations focused on understanding credit score behavior.
# Chart Types Used:
- Boxplots
- Countplots
# Key Comparisons:
- Delay from Due Date vs Credit Score
- Number of Delayed Payments vs Credit Score
- Credit Utilization Ratio vs Credit Score
- Outstanding Debt vs Credit Score
- Credit Mix vs Credit Score
- Payment Behaviour vs Credit Score
- Income vs Credit Score
- Month vs Credit Score

---

# Key Insights
- **Payment behavior is the strongest determinant of credit score**
→ Customers with higher payment delays tend to have poorer credit scores
- **Credit utilization and outstanding debt negatively impact creditworthiness**
→ Higher credit usage and debt levels are associated with lower credit scores
- **Credit mix plays a significant role in credit score**
→ A balanced and healthy credit mix leads to better credit scores
- **Income has limited influence on credit score**
→ Higher income does not necessarily guarantee better creditworthiness
- **Demographic and temporal factors have minimal impact**
→ Age, occupation, and time (month) show little to no significant effect on credit score

---

# Business Impact
- Enables better credit risk assessment
- Helps identify high-risk customers early
- Supports data-driven lending decisions
- Reduces chances of loan defaults

---

# Limitations
- Over-reliance on single factors may misclassify customers
- Temporary financial issues may affect behavior-based insights

---

# Outcomes
- Identified key behavioral drivers of credit score
- Transformed messy data into meaningful features
- Built a structured EDA workflow
- Generated actionable insights for financial decision-making

---

# Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn

---

# Conclusion
This project highlights that creditworthiness is driven more by financial behavior than income or demographics, emphasizing the importance of payment discipline and responsible credit usage.

---

# Dataset
The dataset is not included in this repository due to size limitations.

You can download it from the following link:
https://drive.google.com/file/d/1PWWyZqqtqegWn1khWyd3R1-3g__2TDZ6/view?usp=drive_link

After downloading, place the file in the same directory as the notebook before running the code.
