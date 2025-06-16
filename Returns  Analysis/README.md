# 📦 Storytelling with Data – Superstore Returns Analysis (Tableau)

## 📝 Project Overview

In this project, I analyzed customer returns for a fictional Superstore, with the objective of identifying patterns and root causes behind returned orders. The analysis was designed for presentation to the company's CEO, providing clear and actionable insights through effective data storytelling using **Tableau**.

---

## 📂 Dataset

The project uses the `Superstore.xls` dataset, which includes:

- **Orders**: Detailed order information including dates, sales, customer data, and product categories.
- **Returns**: A table listing returned orders.

A LEFT JOIN was used to merge `Returns` into `Orders`, with a calculated `Returned` field created to convert "Yes" to `1` and nulls to `0`, enabling accurate return rate calculations.

---

## 🔍 Analysis Breakdown

### 📈 What is Causing Returns?

Several Tableau worksheets were built to analyze the return patterns:

1. **Sales vs Returns (Scatterplot)**  
   Explored the correlation between total sales and returns by product subcategory. Identified that higher sales are generally associated with higher return volumes.

2. **Return Rate by Product Category (Bar Chart)**  
   Compared return rates across Furniture, Office Supplies, and Technology. Rates were relatively consistent, with minor category-level differences.

3. **Return Rate by Customer (Bar Chart with Filter)**  
   Analyzed frequent returners by filtering out customers with only one order. Helped identify repeat returners.

4. **Return Rate by Geography (Map View)**  
   Visualized return patterns by state to identify regions with higher return tendencies.

5. **Return Rate Over Time (Line Chart)**  
   Assessed monthly return rate trends to reveal potential seasonal spikes in returns.

6. **Composite Charts (Category + Date)**  
   Combined views by product category and month to uncover detailed patterns and intersections between time and product type.

---

## 🧭 Dashboard Development

### 🛠️ Process

- Created three hand-drawn wireframes (low-fidelity mockups) for potential dashboard layouts.
- Selected the best mockup and built a dashboard template in Tableau using containers.
- Integrated the analytical worksheets into the template.
- Finalized the dashboard with interactive filters, clear titles, and explanatory labels.

### 📌 Dashboard Highlights

- Return rate trends at a glance
- Geographic heatmap for state-level insights
- Filters for product category, date, and customer segment
- Developer-friendly layout for monitoring and diagnostics

---

## 📽️ Presentation & Storytelling

### 📋 Story Arc

The presentation included the following key components:

- **Summary of Return Trends**  
  Outlined why return rates matter, and how they should be measured (return rate vs total count vs return cost).

- **Root Cause Analysis**  
  Explained the factors contributing to high returns with visual evidence.

- **Dashboard Walkthrough**  
  Demonstrated how to navigate the dashboard, apply filters, and interpret each visual.

- **Actionable Insights**  
  Suggested next steps such as targeted quality control, regional strategy adjustments, and customer feedback loops.

---

## 🌐 Tableau Public Link

📊 **[View the Full Dashboard on Tableau Public](#)**  
> _(*Insert your actual Tableau Public link here once published*)_

---

## 💡 Tools & Skills Used

- **Tableau** for data visualization and storytelling  
- **Excel** for data preparation  
- **Data Cleaning & Transformation** using calculated fields and relationships  
- **Storyboarding & Dashboard Design** based on business goals

---

## 📦 Files Included

- `README.md` – Project summary  
- `.twbx` – Tableau workbook (available upon request or zipped upload)  
- `.pdf` – Project screenshots and dashboard documentation  
- Mock-up images (low-fidelity dashboard sketches)

---

## 📈 Key Outcomes

- Developed a reusable dashboard to monitor return trends
- Identified actionable patterns in customer, product, and regional return behaviors
- Practiced presenting insights through a structured story arc





