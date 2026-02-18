# SectionA_Group12_Loan_Default_Risk_Analysis_Dashboard

# 🏦 Loan Default Risk Analysis Dashboard

## 📌 Project Overview

This project analyzes borrower data to identify high-risk customer segments that are more likely to default on loans. The objective is to support data-driven lending decisions and reduce overall credit risk.

The dashboard provides insights into demographic and financial factors that influence loan default behavior.

---

## 🎯 Problem Statement

Which customer segments are most likely to default on loans, and how can lending decisions be optimized to reduce credit risk?

---

## 💼 Business Context

Loan defaults increase non-performing assets (NPAs), reduce profitability, and expose financial institutions to credit risk. Banks must balance growth with risk by identifying high-risk borrowers and optimizing approval strategies.

This project uses structured loan data to segment borrowers and detect patterns associated with default probability.

---

## 📊 Dataset Information

- **Dataset Name:** Loans50K Dataset  
- **Source:** University of Wisconsin–La Crosse Data Science Project Repository (2018)  
- **Records:** ~50,000  
- **Type:** Structured tabular data  

---

## 🔍 Key Features of the Dashboard

### ✅ KPI Overview
- Total Loans
- Total Defaulted Loans
- Default Rate (%)
- Average Loan Amount
- Average Loan Amount (Default vs Non-Default)

### ✅ Risk Segmentation
- Default Rate by Age Group
- Default Rate by Income Level
- Default Rate by Employment Length
- Loan Amount Analysis

### ✅ Comparative Analysis
- Income vs Loan Amount (Scatter Plot)
- Segment Concentration
- Risk Distribution Visualization

---

## 📈 Key KPIs

1. **Default Rate (%)**
2. **Segment-wise Default Rate (%)**
3. **Average Loan Amount (Default vs Non-Default)**
4. **High-Risk Segment Concentration (%)**

---

## 🧠 Expected Insights

- Lower income groups may exhibit higher default rates.
- Shorter employment length may increase default probability.
- Higher loan amounts may correlate with higher risk exposure.

---

## 🛠 Tools Used

- Google Sheets (Data Cleaning & Dashboard)
- Excel (Visualization Prototyping)
- Data Analysis Techniques (Segmentation & Risk Metrics)

---

## 📌 Project Objectives

- Identify high-risk borrower segments
- Quantify default patterns
- Support risk-based lending decisions
- Improve credit portfolio stability

---

## 🚀 Strategic Impact

The insights from this dashboard can help financial institutions:

- Improve underwriting standards
- Reduce loan default rates
- Implement risk-based pricing
- Strengthen credit risk management

---

## 🚀 Data Log

| Date       | Affected Area        | Action Performed          | Reason                                                                | By Whom    |
|------------|---------------------|----------------------------|-----------------------------------------------------------------------|------------|
| 2026-12-02 | Loan Data Sheet     | Data Cleaning              | Initial data preparation and consistency check.                       | Chinmay    |
| 2026-12-02 | Client Status Tab   | Filter Applied             | Segmenting active vs. defaulted accounts for initial review.          | Chinmay    |
| 2026-12-02 | Risk Scoring        | Calculation Formula Added  | Establishing baseline risk scores using new weighted average.         | Chinmay    |
| 2026-12-02 | Reporting Dashboard | Placeholder Creation       | Setting up structure for final dashboard elements.                    | Chinmay    |
| 2026-13-02 | Loan_ID Column      | Duplicate Check            | Ensuring unique identification for all loan records.                  | Kavya      |
| 2026-13-02 | Interest Rate       | Outlier Removal            | Standardizing interest rates by removing extreme values.              | Jashwitha  |
| 2026-13-02 | Income & Debt Columns | Data Transformation      | Converting currency strings to numerical format for calculation.      | Akshay     |
| 2026-13-02 | Age Feature         | Feature Engineering        | Creating age groups (buckets) for demographic segmentation.           | Gaurav     |
| 2026-14-02 | Payment History     | VLOOKUP/MATCH              | Linking payment status from separate log sheet.                       | Harshita   |
| 2026-14-02 | Loan_ID Column      | Filter Applied             | Focusing on high-risk loans (Default=TRUE) for deep dive.             | Kavya      |
| 2026-15-02 | Pivot Table 1       | Creation                   | Summarizing default count by state/region.                            | Jashwitha  |
| 2026-15-02 | Charts Sheet        | Bar Chart Added            | Visualizing top 5 states with highest default rates.                  | Akshay     |
| 2026-15-02 | Data Validation     | Conditional Formatting     | Highlighting rows where loan amount exceeds $500,000.                 | Gaurav     |
| 2026-15-02 | Date Columns        | Date Format Update         | Changing date format to YYYY-MM-DD for consistency.                   | Harshita   |
| 2026-16-02 | Monthly Payment     | Calculation Formula Added  | Calculating DTI (Debt-to-Income) ratio column.                        | Kavya      |
| 2026-16-02 | Pivot Table 2       | Creation                   | Analyzing default rate against DTI categories.                        | Jashwitha  |
| 2026-16-02 | Charts Sheet        | Pie Chart Added            | Showing distribution of loan types (e.g., Mortgage, Personal, Auto).  | Akshay     |
| 2026-17-02 | Reporting Dashboard | Slicer Added               | Allowing dynamic filtering by 'Loan Type' on all charts.              | Gaurav     |
| 2026-17-02 | Header Row          | Freeze Panes               | Locking the header row for easy navigation during scrolling.          | Harshita   |
| 2026-17-02 | Column C            | Column Renamed             | Renamed 'CreditScore' to 'FICO Score' for clarity.                    | Kavya      |
| 2026-17-02 | Formula Auditing    | Error Check                | Identifying and correcting #DIV/0! errors in ratio calculations.      | Jashwitha  |
| 2026-17-02 | Pivot Table 3       | Creation                   | Summarizing average credit score per default status.                  | Akshay     |
| 2026-17-02 | Charts Sheet        | Line Chart Added           | Tracking the average loan amount issued over time.                    | Gaurav     |
| 2026-17-02 | Reporting Dashboard | Integration                | Embedding all three pivot tables and charts into the dashboard.       | Harshita   |
| 2026-17-02 | Sheet Tabs          | Naming Conventions         | Renaming sheets (e.g., 'Sheet1' to 'Raw Data').                       | Kavya      |
| 2026-18-02 | Access Permissions  | Sharing Updated            | Granting 'View Only' access to management team.                       | Jashwitha  |
| 2026-18-02 | Data Input Area     | Protection Added           | Preventing accidental edits to the raw source data range.             | Akshay     |
| 2026-18-02 | Risk Model Parameters | Sensitivity Analysis     | Adjusting risk weights to see impact on predicted defaults.           | Gaurav     |
| 2026-18-02 | Dashboard Text      | Review & Polish            | Adding descriptive titles and labels for better interpretation.       | Harshita   |
| 2026-18-02 | Loan Term Column    | Missing Value Imputation   | Filling blank loan terms with the median value for that loan type.    | Kavya      |
| 2026-18-02 | Documentation Tab   | Project Notes Added        | Logging key decisions regarding data exclusions and methodology.      | Jashwitha  |



## 📎 Repository Structure

