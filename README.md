
# Python-Bank-Loan-Analysis-Project

### Project Overview

This project presents a comprehensive Python-based analysis of bank loan data to evaluate loan application trends, funded amounts, repayment performance, borrower profiles, and loan risk.
The project transforms raw financial data into meaningful business insights through Exploratory Data Analysis (EDA), statistical analysis, and data visualization.
The analysis focuses on understanding good loans and bad loans, monitoring monthly lending performance, identifying funding patterns across different states, and examining loan distribution based on borrower characteristics.

---

### Table of Contents
- [Problem Statement](#problem-statement)
- [Project Objectives](#project-objectives)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Analysis & Features](#analysis--features)
- [Visualizations](#visualizations)
- [Key Findings](#key-findings)
- [Business Recommendations](#business-recommendations)
- [Project Structure](#project-structure)
- [Conclusion](#conclusion)
- [Author](#author)

---

### Problem Statement

Financial institutions need to monitor loan applications, lending performance, repayment behavior, and borrower risk to make informed lending decisions.
The objective of this project is to analyze historical bank loan data and identify patterns in loan applications, funded amounts, repayments, loan status, and borrower characteristics.

The analysis aims to answer the following business questions:
- How many loan applications were received?
- What is the total amount funded and received?
- What percentage of loans are classified as good loans and bad loans?
- How does loan performance change over time?
- Which states contribute the highest loan funding?
- Which loan purposes account for the largest funded amounts?
- How do employment length, loan term, and home ownership relate to lending activity?

---

### Project Objectives

- Analyze overall loan application performance.
- Calculate total loan applications, funded amounts, and received payments.
- Evaluate good loan and bad loan performance.
- Compare Month-to-Date (MTD) and overall lending metrics.
- Analyze monthly loan application and funding trends.
- Identify state-wise loan funding distribution.
- Examine loan distribution by term and employment length.
- Analyze loan funding by purpose and home ownership.
- Generate meaningful business insights and recommendations.

---

### Dataset

The project uses an Excel dataset named `financial_loan.xlsx`.

**Dataset Overview:**

| Attribute | Details |
|---|---|
| Dataset Name | financial_loan.xlsx |
| Total Records | 38,576 |
| Total Columns | 24 |
| File Format | Excel (.xlsx) |
| Analysis Period | 2021 |
| Data Type | Financial and Loan Data |

**Important Dataset Columns:**
- `id` – Unique loan application identifier.
- `address_state` – Borrower's state.
- `application_type` – Type of loan application.
- `emp_length` – Employment length.
- `emp_title` – Employment title.
- `grade` – Loan grade.
- `home_ownership` – Borrower's home ownership status.
- `issue_date` – Loan issue date.
- `loan_status` – Loan repayment status.
- `purpose` – Purpose of the loan.
- `term` – Loan repayment term.
- `annual_income` – Borrower's annual income.
- `dti` – Debt-to-income ratio.
- `installment` – Monthly loan installment.
- `int_rate` – Loan interest rate.
- `loan_amount` – Amount funded.
- `total_acc` – Total credit accounts.
- `total_payment` – Total amount received.

---

### Tools & Technologies

- **Python** – Programming and data analysis.
- **Jupyter Notebook** – Interactive development environment.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Plotly Express** – Interactive visualizations.
- **Microsoft Excel** – Dataset storage and management.

---

### Data Cleaning & Preparation

The initial data inspection and preparation involved:
- Importing the Excel dataset using Pandas.
- Inspecting the first and last five records.
- Checking dataset dimensions (rows and columns).
- Examining column names and data types.
- Generating descriptive statistical summaries.
- Working with date columns for monthly analysis.
- Grouping and aggregating data based on different business dimensions.
- Preparing calculated metrics for loan performance analysis.

---

### Analysis & Features

The project explores several important financial performance metrics and lending dimensions.

**1. Overall Loan Performance**

- Total Loan Applications
- Month-to-Date (MTD) Loan Applications
- Total Funded Amount
- MTD Funded Amount
- Total Amount Received
- MTD Amount Received
- Average Interest Rate
- Average Debt-to-Income (DTI) Ratio

**2. Good Loan Analysis**

Good loans are classified as loans with the following statuses:
- Fully Paid
- Current

Metrics analyzed:
- Good Loan Applications
- Good Loan Funded Amount
- Good Loan Amount Received
- Good Loan Application Percentage

**3. Bad Loan Analysis**

Bad loans are classified as loans with the following status:
- Charged Off

Metrics analyzed:
- Bad Loan Applications
- Bad Loan Funded Amount
- Bad Loan Amount Received
- Bad Loan Application Percentage

**4. Monthly Trend Analysis**

- Monthly Loan Applications
- Monthly Funded Amount
- Monthly Amount Received

**5. Borrower & Loan Analysis**

- State-wise Loan Funding
- Loan Funding by Term
- Loan Funding by Employment Length
- Loan Funding by Loan Purpose
- Loan Funding by Home Ownership

---

### Visualizations

The project uses different visualization techniques to understand loan performance and lending patterns.

| Visualization | Purpose |
|---|---|
| Area & Line Chart | Monthly funded amount |
| Area & Line Chart | Monthly amount received |
| Area & Line Chart | Monthly loan applications |
| Horizontal Bar Chart | State-wise funded amount |
| Doughnut Chart | Funded amount by loan term |
| Horizontal Bar Chart | Funding by employment length |
| Horizontal Bar Chart | Funding by loan purpose |
| Treemap | Funding by home ownership |

---

### Key Findings

Based on the analysis of **38,576 loan applications**, the following insights were identified:

1. **Overall Loan Performance:** The analysis reports **38,576 loan applications**, **$435.76 million in total funded amount**, and **$473.07 million in total amount received**.

2. **Average Interest Rate:** The portfolio has an average interest rate of **12.05%**, indicating the average borrowing rate across the analyzed loans.

3. **Average DTI Ratio:** The average Debt-to-Income (DTI) ratio is **13.33%**, providing insight into borrowers' debt obligations relative to their income.

4. **Good Loan Performance:** **33,243 applications (86.18%)** are classified as good loans, with **$370.22 million funded** and **$435.79 million received**.

5. **Bad Loan Performance:** **5,333 applications (13.82%)** are classified as bad loans, with **$65.53 million funded** and **$37.28 million received**.

6. **MTD Loan Applications:** The latest month represented in the dataset recorded **4,314 loan applications**.

7. **MTD Funding Performance:** The latest month recorded **$53.98 million in funded loans** and **$58.07 million in total payments received**.

8. **Loan Distribution Analysis:** The project examines funding patterns across different states, employment lengths, loan terms, loan purposes, and home ownership categories.

---

### Business Recommendations

- **Monitor Loan Defaults:** Regularly monitor charged-off loans to identify potential credit risks and improve lending strategies.
- **Improve Borrower Assessment:** Evaluate borrower income, debt-to-income ratios, employment history, and credit profiles before approving loans.
- **Track Monthly Performance:** Monitor loan applications, funded amounts, and repayments to identify changes in lending activity.
- **Optimize Loan Portfolio:** Analyze loan performance across different terms, grades, and purposes to understand risk distribution.
- **Strengthen Risk Management:** Develop appropriate lending policies based on borrower risk profiles and historical repayment patterns.
- **Monitor Geographic Performance:** Evaluate state-wise funding and repayment trends to support informed lending decisions.

---

### Project Structure

```text
python-bank-loan-analysis/
│
├── README.md
│
├── Bank Loan Analysis Project.ipynb
│
└── financial_loan.xlsx
```

---

### Conclusion

The Bank Loan Analysis project uses Python to transform financial loan data into meaningful business insights.
It analyzes loan application trends, funded amounts, repayment performance, good and bad loan distribution, and borrower characteristics.
Through Exploratory Data Analysis and data visualization, the project helps identify lending patterns, evaluate loan portfolio performance, and understand potential credit risks.
This project demonstrates practical skills in Python programming, data manipulation, exploratory data analysis, data visualization, and business insight generation.

---

### Author


