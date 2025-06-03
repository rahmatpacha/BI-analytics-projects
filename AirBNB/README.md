# 🗽 NYC Airbnb Market Analysis – Sprint 1: Spreadsheet Data Analysis

## 📊 Project Overview

This project was completed as part of **Sprint 1** in TripleTen’s Business Intelligence Analyst program. The objective was to support a client interested in investing in Manhattan’s vacation rental market by using spreadsheet tools (Excel/Google Sheets) to analyze Airbnb data and provide actionable investment insights.

---

## 🏙️ Business Objective

The client wants to know:

- Which neighborhoods and property sizes are most attractive for vacation rentals?
- How much money do these top-performing listings generate?

The goal is to help the client identify profitable opportunities and make informed real estate investment decisions.

---

## 📁 Dataset

- **Listings** data: Property-level details including bedrooms, neighborhood, and reviews.
- **Calendar** data: Daily availability and pricing information over a 30-day period.

---

## 🔧 Methodology

### 1. **Data Cleaning**
- Cleaned inconsistent values in the `neighbourhood` and `bedrooms` columns.
- Created new fields:
  - `neighbourhood_clean`
  - `bedrooms_clean`
- Documented cleaning steps in a dedicated sheet.
- Preserved original data in a raw copy.

### 2. **Pivot Tables**
- Identified top 10 neighborhoods using `number_of_reviews_ltm` as a proxy for rental frequency.
- Analyzed property sizes (number of bedrooms) to determine popularity.
- Cross-referenced neighborhood preferences by property size.

### 3. **Revenue Analysis**
- Labeled top listings based on popularity and size per neighborhood.
- Created a new `revenue_earned` column in the calendar data based on `adjusted_price` when rented.
- Used `SUMIF()` to calculate total 30-day revenue, then estimated annual revenue by multiplying by 12.

---

## 📌 Key Insights

### 🔝 Top 3 Neighborhoods by Review Volume
- Hell's Kitchen  
- Flatiron District  
- East Harlem  

These areas showed the highest engagement, indicating strong demand.

### 🛏️ Most Popular Property Sizes
- Studio apartments  
- 1-bedroom units  
- 2-bedroom units  

### 🏘️ Property Size Preference in Harlem
- **1-bedroom listings** were the most popular in Harlem and several other neighborhoods.

### 💰 Revenue Potential
- Top listings generated up to **$60,000+ in estimated annual revenue** based on their 30-day performance.
- Studio units in Midtown, in particular, offered high return potential.

---

## 💼 Deliverables

- Cleaned dataset with documentation of all transformations.
- Interactive pivot tables to explore neighborhood/property size trends.
- Revenue model calculating estimated yearly earnings per listing.
- Executive summary outlining strategic investment recommendations.

---

## 📎 Project Files

