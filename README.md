# 🏦 FinTrust Bank: Credit Risk & Loan Portfolio Intelligence

[![Live Dashboard](https://img.shields.io/badge/Live_Dashboard-Bricks-blueviolet?style=for-the-badge)](https://app.thebricks.com/file/9390205d-c8fe-4a4a-9fb3-23f4684418bf)
[![Tech Stack](https://img.shields.io/badge/Tech_Stack-Python_|_SQL_|_Power_BI-blue?style=for-the-badge)](#-tech-stack)

> **Role:** Data Analyst Intern (Simulated) | **Department:** Risk Analytics & Business Intelligence  
> **Business Objective:** Analyze historical loan application data to isolate high-risk customer segments, evaluate portfolio exposure, and deliver actionable credit policy guardrails to reduce future financial defaults.

---

## 🔗 Live Interactive Assets
* **👉 [View Interactive Dashboard & Embedded Business Report (Live on Bricks)](https://app.thebricks.com/file/9390205d-c8fe-4a4a-9fb3-23f4684418bf)**

---

## 💼 Business Problem & Stakeholders
Approving loans for applicants who later default causes substantial, preventable financial losses for FinTrust Bank. This project delivers a diagnostic analytics platform to answer critical portfolio health questions for:
* **Chief Risk Officer (CRO):** Needs high-level portfolio KPIs and capital-at-risk trends.
* **Credit Risk Manager:** Seeks key risk parameters to refine credit scoring models.
* **Underwriting Team:** Requires clear, data-driven guidelines for daily application approvals.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Data ETL & Pre-processing:** Python (Pandas) for data cleansing, handling outliers, and missing value imputation.
* **Relational Querying:** SQL (PostgreSQL/MySQL) using CTEs, Window Functions, and CASE statements.
* **Data Modeling:** DAX (Power BI Desktop) for customized metrics, binned scales, and conditional logic.
* **Data Storytelling & UX:** Bricks (for embedding dynamic qualitative reports alongside interactive dashboards).

---

## ⚙️ Project Pipeline
### Phase 1: Business Understanding ✅
*   Defined the scope, identified core risk factors, mapped stakeholders, and established the key business questions[cite: 1].

### Phase 2: Data Pre-processing (Python) ✅
*   **Outlier Resolution:** Handled impossible demographic data points.
*   **Imputation & Cleaning:** Resolved missing interest rate variables using subgroup medians[cite: 1].
*   **Integrity Checks:** Performed duplicate checks and executed strict data-type casting[cite: 1].

### Phase 3: Exploratory Data Analysis (Python) ✅
*   Performed univariate and bivariate analysis to isolate primary risk factors[cite: 1].
*   Generated statistical summaries to map demographic spreads[cite: 1].

### Phase 4: SQL Business Analysis ✅
*   Constructed relational queries using **CTEs, Window Functions, Aggregate Groupings, and conditional CASE statements** to run deep-dive risk segmentations[cite: 1].

### Phases 5 & 6: Power BI & Bricks Narrative Reporting ✅
*   Designed an interactive, multi-tab dashboard layout combining diagnostic visuals with **embedded, report-style narrative insights** directly on the canvas[cite: 1].

---

## ⚙️ Project Pipeline

### Phase 1: Business Understanding ✅
* Defined the scope, identified core risk factors, mapped stakeholders, and established the key business questions[cite: 1].

### Phase 2: Data Pre-processing (Python) ✅
* **Outlier Resolution:** Handled impossible demographic data points.
* **Imputation & Cleaning:** Resolved missing interest rate variables using subgroup medians[cite: 1].
* **Integrity Checks:** Performed duplicate checks and executed strict data-type casting[cite: 1].

### Phase 3: Exploratory Data Analysis (Python) ✅
* Performed univariate and bivariate analysis to isolate primary risk factors[cite: 1].
* Generated statistical summaries to map demographic spreads[cite: 1].

### Phase 4: SQL Business Analysis ✅
* Constructed relational queries using **CTEs, Window Functions, Aggregate Groupings, and conditional CASE statements** to run deep-dive risk segmentations[cite: 1].

### Phases 5 & 6: Power BI & Bricks Narrative Reporting ✅
* Designed an interactive, multi-tab dashboard layout combining diagnostic visuals with **embedded, report-style narrative insights** directly on the canvas[cite: 1].

---

## 💻 SQL Analysis & Query Snippets
[![SQL Repository](https://img.shields.io/badge/View_SQL_Queries-GitHub-181717?style=flat&logo=github)](https://github.com/ethicalinsight/credit-risk-analysis-sql)

*Detailed PostgreSQL/MySQL scripts containing CTEs, Window Functions, and cohort analysis utilized during the business analysis phase can be found in the dedicated SQL repository linked above.*

---

## 🧠 Strategic Business Recommendations
Based on the diagnostic analytics, the following changes are proposed to the Credit Risk Committee:

1. **Instate a Hard-Limit Cap on High-Leverage Loans:** The *Income vs. Loan Amount Exposure* scatter plot reveals a critical default cluster when the Loan-to-Income (LTI) ratio exceeds **30%**[cite: 1]. Introduce automated system blocks for any application exceeding this threshold[cite: 1].
2. **Apply Probationary Guardrails on New Employees:** Borrowers with `< 1 Year` of employment (`emp_length = 0`) carry an elevated default trend[cite: 1]. Restrict maximum exposure to $10,000 for this segment until 12 months of employment are verified.
3. **Optimize Risk-Based Pricing on Unsecured Intents:** Unsecured Medical and Venture loans show a default rate nearly double that of Home Improvement loans[cite: 1]. Adjust the credit policy to require a 1.5%–2.5% interest rate risk premium on these categories to offset portfolio losses.

---
