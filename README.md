# 📊 Bank Loan Analytics Dashboard

A data analytics project focused on analyzing bank loan performance, revenue metrics, and risk indicators using interactive dashboards.

This project transforms raw banking data into meaningful insights for decision-making through data cleaning, KPI calculations, and visualization.

---

# 🚀 Project Overview

The objective of this project is to analyze loan portfolio data to understand loan performance, revenue generation, and potential risk factors.

A centralized dashboard was created to monitor key metrics such as loan disbursement, collection performance, default rates, and customer demographics.

The insights generated help support data-driven financial decisions.

---

# 🎯 Objectives

- Analyze loan portfolio performance  
- Identify default and delinquency risks  
- Track loan distribution across states and branches  
- Understand customer demographics and product demand  
- Build a centralized dashboard for monitoring KPIs  

---

# 📂 Dataset Information

**Total Rows:** ~66,000  
**Total Columns:** 15+  
**Domain:** Banking / Loan Analytics  

### Key Columns

- Loan ID  
- Funded Amount  
- Total Interest  
- Collection  
- State  
- Branch  
- Religion  
- Grade  
- Age  
- Product Group  
- Loan Status  
- Default Flag  
- Delinquent Flag  
- Verification Status  

---

# 🛠 Tools & Technologies

- Tableau – Dashboard & Visualization  
- Power BI – Data modeling & analytics  
- Excel – Data cleaning and analysis  

---

# 📈 Key Performance Indicators (KPIs)

- Total Funded Amount  
- Total Loans  
- Total Collection  
- Total Interest  
- Default Loan Rate  
- Delinquent Loan Rate  
- Default Loan Count  
- Delinquent Client Count  
- Non-Verified Loan %

### KPI Calculation Logic

Total Funded Amount = SUM(Funded Amount)

Total Collection = SUM(Collection)

Total Interest = SUM(Total Interest)

Total Loans = COUNT(Loan ID)

Default Rate = Default Count / Total Loans * 100

Delinquent Rate = Delinquent Count / Total Loans * 100

Non Verified % = Not Verified Count / Total Loans * 100

Profit Insight = Total Collection - Funded Amount

---

# 📊 Dashboard Highlights

**Total Funded Amount:** ₹733M  
**Total Collection:** ₹808M  
**Default Rate:** 1.6%  
**Delinquent Rate:** 10.8%  

**Highest Loan State:** Uttar Pradesh  
**Top Revenue Branch:** Mathura  

---

# 📊 Key Insights

### State Wise Loans
- Uttar Pradesh and Punjab dominate loan distribution.
- Bihar, Haryana, Rajasthan, Odisha, Assam, and West Bengal contribute moderately.
- Himalayan states show minimal loan activity.

### Religion Wise Loans
Loan uptake is highest among Hindus, followed by Sikhs and Muslims, while Christians represent a smaller portion of the dataset.

### Product Group Analysis
Loan demand is concentrated in:
- Housing
- Services
- Business

Consumer goods and niche products have lower demand.

### Age Group Distribution
- 26–35 Age Group: 35%
- 36–45 Age Group: 32%

Together they represent more than 65% of borrowers, showing strong demand among working professionals.

### Loan Grade Analysis
- Grade B dominates with around 30% of total loans.
- Grades A and C together contribute around 40%.
- Lower grades represent a much smaller share.

---

# 📉 Loan Status Distribution

- Active Loans: 55%
- Fully Paid Loans: ~25%
- Remaining loans include transferred, insured, or cancelled.

This indicates a largely active loan portfolio with relatively low risk exposure.

---

# 📌 Recommendations

- Reduce delinquent loans through better monitoring
- Improve verification processes for loan approvals
- Focus on high-performing branches
- Strengthen credit checks for lower-grade borrowers
- Target the 26–35 age group for future growth

---

# ⚡ Challenges Faced

- Data cleaning and handling missing values
- Calculation errors during KPI creation
- Date formatting issues
- Designing optimized dashboards

---

# 📚 Key Learnings

- Data cleaning and preprocessing
- KPI calculation logic
- Tableau calculated fields
- Dashboard design and visualization
- Data storytelling with analytics

---

# 📷 Dashboard Preview

(Add your dashboard screenshots here)

Example:

![Dashboard Preview](<img width="1920" height="1080" alt="Dashboard2" src="https://github.com/user-attachments/assets/24bf0698-6a68-42c0-8d87-e83475fb1e2a" />
)

---

# 🏁 Conclusion

The analysis shows that the bank’s loan portfolio is financially strong, with total collections exceeding funded amounts.

While the default rate remains low, there is room for improvement in managing delinquent loans.

The dashboard enables performance monitoring and supports data-driven decision making.
