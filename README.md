# PAYSWIFT GHANA: STRATEGIC GROWTH & RISK HUB

This repository contains the end-to-end business intelligence pipeline for **PaySwift Ghana**, transitioning raw fintech data into actionable product strategies to mitigate a **34% churn rate** and **33% loan default rate**.

---

## Dashboard Architecture & Artifacts

### 1. Data Cleaning & Diagnostics (Excel)

Initial data wrangling, categorical standardization, and logical imputation were performed in Excel to establish baseline metrics.

* **Key Insight:** Active users logged **16.86 transactions/month** compared to just **4.09** for churning users.

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/7c57541f-976a-4e65-8141-8eeece008130" />


### 2. Executive Strategy Overview (Power BI - Page 1)

A clean, light-themed corporate dashboard designed for high-level stakeholders to monitor core product KPIs and portfolio risk.

* **Key Insight:** A clear inverse relationship was mapped between transaction frequency and default risk, validating that app activity acts as a shield against default.

<img width="1280" height="740" alt="image" src="https://github.com/user-attachments/assets/c35e46f3-9246-49d4-b57f-733b86c1f3be" />


### 3. Deep Dive & Behavioral Hub (Power BI - Page 2)

An interactive, high-contrast dark-mode interface utilizing embedded machine learning to identify core behavioral drivers.

* **Key Insight:** The native *Key Influencers* AI visual established that user maturity (age) and transaction frequency are the highest statistical indicators of platform loyalty.

<img width="1280" height="740" alt="image" src="https://github.com/user-attachments/assets/8d8ecdd0-5034-49f8-b369-5a57e31196df" />


### 4. Strategic Feature Valuation Matrix

A specialized breakdown mapping product feature adoption against financial outcomes to isolate retention anchors from churn drivers.

* **Key Insight:** **Savings Trackers** and **Budgeting Tools** maintain a **0% churn rate**, while isolated **Loan Services** experience a **100% churn rate**.

<img width="600" height="338" alt="image" src="https://github.com/user-attachments/assets/1eee27ea-ca2f-489f-868d-1f5be6079cee" />


---

## Tech Stack

* **Excel / Power Query:** Data cleaning, logical imputation, and exploratory pivot tables.
* **Power BI Desktop:** DAX modeling, semantic layer configuration, and custom UI/UX design.
* **Python (Pandas):** Statistical exploration and multivariate correlation analysis.

---

##  Strategic Recommendations

1. **Tiered Credit Access:** Introduce a "Path to Credit" where high-risk demographics (ages 18–25) must maintain consistent transaction volume before unlocking larger micro-loans.
2. **UX-Driven Feature Bundling:** Mandatory integration of the **Budgeting Tool** during the loan application process to force engagement with high-retention features.
3. **Automated Engagement Triggers:** Deploy push-notification pipelines targeting users whose transaction velocity drops below 5/month to intercept churn before account abandonment.
