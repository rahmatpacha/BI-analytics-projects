# 📊 Data Visualization with Tableau – Superstore Profitability Analysis

## 🧾 Project Overview

In this project, I took on the role of a consultant to help the Superstore improve its profitability and avoid bankruptcy. Using Tableau, I developed interactive visualizations to diagnose profit and loss patterns, evaluate advertising strategies, and assess product return behaviors.

The project is structured around three key business challenges: identifying profit/loss centers, planning targeted advertising, and evaluating return patterns — all with the goal of data-driven decision-making.

---

## 📁 Dataset

The analysis was conducted using the `Superstore.xls` dataset, which includes:

- **Orders**: Sales transactions with product, category, profit, customer, and geographic data.
- **Returns**: Contains information on returned orders.

A LEFT JOIN was used to connect Returns to Orders, enabling a full analysis of return behavior alongside profit performance.

---

## 🔍 Analysis Breakdown

### 📈 Part 1: Profits & Losses

- **Top Profit and Loss Centers**:  
  Used visual comparisons of dimension pairs (e.g., Subcategory + Region, Shipping Mode + Product ID) to identify the two largest profit centers and two largest sources of loss.

- **Products to Discontinue**:  
  Identified products with consistently negative profit margins, recommending they be removed from the catalog.

- **Subcategory Focus**:  
  Highlighted three subcategories to focus on for growth and three to deprioritize, based on overall profitability and strategic opportunity.

### 📣 Part 2: Advertising ROI

- **Best States and Months to Advertise**:  
  Calculated average monthly profit per unit in each state to identify top-performing combinations of state and time for advertising.

- **Ad Spend Recommendations**:  
  Applied a 1/5 profit-to-advertising ratio to determine how much the company could reasonably invest in advertising by location and season.

### 📦 Part 3: Returned Items

- **Return Rate Calculation**:  
  Created a calculated field where “Yes” = 1 and null = 0 to accurately measure return rates.

- **Highest Return Products and Customers**:  
  Identified products and customers with abnormal return rates, signaling quality or satisfaction issues.

- **Profit vs Return Rate by Dimension**:  
  Compared average profit against average return rate across dimensions (e.g., State, Shipping Mode) to support recommendations on which practices to continue or revise.

---

## 📊 Tableau Public Link

👉 **[View Interactive Dashboard on Tableau Public](#)**  
> _(*Replace with your actual Tableau Public URL*)_

---

## 💼 Business Value

- Improved profit visibility by product and region
- Clear return on ad spend calculations to guide marketing
- Actionable product insights to reduce return losses and discontinue poor performers

---

## 🧰 Tools & Techniques

- **Tableau**: Visualization and dashboard design  
- **Data Modeling**: Table joins and calculated fields  
- **Analytical Thinking**: Business logic applied to sales, profit, and return data  
- **Storytelling**: Used visuals to justify decisions and drive strategic outcomes

---

## 📦 Files Included

- `README.md` – Project overview and summary  
- `.twbx` – Tableau workbook (available upon request or zipped upload)  
- `.pdf` – Screenshots and static visuals  
- Supporting images and mockups if applicable

---

## ✅ Key Outcomes

- Built a data-backed visual story to aid executive decision-making
- Identified wasteful products, customers, and operational inefficiencies
- Supported strategic investment in ads with ROI-driven insights



