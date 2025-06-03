# 📈 Business Analytics Project – E-commerce Event Log Analysis

## 🧭 Sprint 3: Business Analytics (TripleTen)

This project was completed as part of Sprint 3 of TripleTen’s Business Intelligence Analyst program. In this challenge, I was hired as a **Junior Analyst** at a fictional e-commerce company to transform raw user event logs into actionable business insights. This analysis involved funnel building, cohort analysis, and retention metrics — all using spreadsheet tools.

---

## 🛒 Business Context

The company captures every interaction users have on its website, from product views to purchases. My task was to analyze these event logs to answer three critical business questions:

1. **How well does the website convert views into purchases?**
2. **How do user retention rates change over time across different customer cohorts?**
3. **What actions can be taken to improve conversion and retention?**

---

## 🧰 Tools Used

- **Google Sheets / Excel**
- Pivot Tables
- VLOOKUP, TEXT, DATEDIF, COUNTIF, UNIQUE
- Data transformation & organization techniques

---

## 📊 Project Structure

### 📌 Part 1: Conversion Funnel

- Built a 3-step funnel: **Product Views → Cart Opens → Purchases**
- Counted **unique users** at each step
- Calculated:
  - **Total Conversion Rate** (Views → Purchase)
  - **Step-by-step Conversion Rates** (e.g. View → Cart, Cart → Purchase)

### 📌 Part 2: Cohort Analysis Preparation

- Filtered purchase events into a dedicated sheet (`purchase_activity`)
- Identified each user's **first purchase date**
- Created helper columns:
  - `event_month`
  - `first_purchase_month`
  - `cohort_age` (months since first purchase)

### 📌 Part 3: Retention Rate Calculation

- Grouped users into **monthly cohorts**
- Created a pivot table (`cohort_analysis`) to track repeat purchases over time
- Built a **retention matrix** showing the % of users from each cohort who returned in subsequent months

### 📌 Part 4: Presentation & Documentation

- Filled out the **Executive Summary** with key findings:
  - Funnel performance
  - Retention trends
- Documented:
  - Dataset assumptions
  - Calculation methods
  - Insights
- Organized sheets using a clean, professional layout
- Added a **Table of Contents** and froze headers for usability

---

## 📈 Key Insights

### 🔻 Funnel Performance

- Drop-off was highest between **Cart Open → Purchase**, indicating friction at the checkout stage.
- Only a small percentage of users who viewed products ended up purchasing.

### 📆 Retention Metrics

- Initial cohorts showed strong engagement in the first month (age 0), with significant declines by month 2–3.
- The most recent cohorts showed slightly improved retention, suggesting onboarding changes may be effective.

---

## 🗂️ File Structure


