# Marketing Funnel Analysis & CRM Data Quality  
**Olist – Brazil Marketplace**

## 📌 Project Overview
This project analyzes a real-world marketing funnel dataset from Olist (Brazil marketplace) with a focus on **CRM data hygiene, funnel performance, cohort analysis, and executive reporting**.

The objective is to simulate how a Data Analyst / CRM Analyst would clean, validate, analyze, and visualize lead lifecycle data for business decision-making.

---

## 🧩 Dataset
- Source: Kaggle – *Marketing Funnel by Olist*
- Data includes:
  - Lead creation and funnel stages
  - Source / channel information
  - Timestamps for stage movement
  - Deal conversion outcomes

---

## 🛠 Tools & Technologies
- **Excel / Google Sheets** – Data cleaning, standardization, deduplication  
- **SQL (SQLite/MySQL/PostgreSQL)** – Funnel analysis, cohorts, SLA metrics  
- **Power BI** – Executive dashboards and KPI visualization  
- **DAX** – Conversion rate, rolling metrics, time-based measures  

---

## 🔍 Part A — Data Cleaning & CRM Hygiene
- Standardized text fields (casing, trimming, consistency)
- Handled missing and invalid values with documented logic
- Designed a **Leads Master table**
- Implemented a **deduplication rule** using business identifiers
- Created a **Data Quality Report** covering:
  - Duplicate rate
  - Top missing fields
  - Data anomalies and fixes

### Outputs
- `leads_clean.csv`
- `dedupe_log.csv`
- `data_quality_report.pdf`

---

## 📊 Part B — SQL Reporting
SQL queries were written to analyze:

- Monthly funnel performance (leads → stages → conversions)
- Cohort conversion rates (7-day and 30-day)
- Time-to-first-funnel-movement (SLA analysis)
- Top-performing acquisition channels
- Data anomalies (date issues, missing transitions, duplicates)

### Outputs
- `queries.sql`
- `sql_outputs.csv / xlsx`

---

## 📈 Part C — Power BI Dashboard
An executive-level Power BI report with:

### Pages
1. **Executive Overview**
   - Total leads, conversions, conversion rate
   - Top sources and time trends
2. **Funnel & Cohorts**
   - Funnel stage drop-offs
   - 7-day and 30-day cohort conversion
3. **Data Quality**
   - Missing values
   - Duplicates prevented
   - Key anomalies

### Key DAX Measures
- Conversion Rate
- Rolling 7-Day Leads
- Median Time to First Funnel Movement

### Outputs
- `Olist_Funnel_Assignment.pbix`
- `dashboard_screenshots.pdf`

---

## 🧠 Key Business Insights
- Identified funnel stages with the highest drop-off
- Highlighted channels with the best balance of volume and conversion
- Recommended CRM validation rules to prevent future data quality issues

---

## 📁 Repository Structure
├── data/
│ ├── leads_clean.csv
│ ├── dedupe_log.csv
├── sql/
│ ├── queries.sql
│ ├── sql_outputs.csv
├── powerbi/
│ ├── Olist_Funnel_Assignment.pbix


---

## ✅ Evaluation Focus
This project emphasizes:
- Data hygiene discipline
- SQL accuracy and clarity
- Practical CRM thinking
- Business-oriented insights
- Clean and explainable dashboards

---

## 📝 Notes
- Dataset is publicly available on Kaggle
- AI tools were used for guidance and validation where appropriate
- All analysis logic and decisions are documented clearly

---

## 👤 Author
**Chawhan Bhoomika**  
Aspiring Data Analyst / CRM Analyst / BI Analyst

