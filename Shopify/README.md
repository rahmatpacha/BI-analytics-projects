# 🛒 Shopify App Analysis – Power BI Project

## 📊 Overview

This Power BI project explores the Shopify App ecosystem using public data scraped from the Shopify App Store. The goal is to identify key factors that contribute to an app's success on the platform. The project is structured into multiple report pages, each addressing specific analytical questions using Power BI visuals and DAX.

---

## 📁 Dataset

The project uses data from `shopify.xlsx`, which includes the following tables:

- **apps**: Contains details of individual apps on the Shopify marketplace.
- **apps_categories**: Join table connecting apps to their multiple categories.
- **categories**: Descriptions and names of app categories.
- **reviews**: Contains user reviews, ratings, and developer replies.

---

## 🧩 Project Structure

The project is divided into four main sections, each represented as a separate page in the Power BI report:

### 🔹 Part 1: App Landscape

- KPI Card showing the total number of unique apps.
- Line Chart showing total review count over time (`lastmod` date).
- Scatterplot comparing review count vs. average rating with annotated insights.

### 🔹 Part 2: Reviews

- Creation of a calculated column `helpful_reviews = rating * (1 + helpful_count)`.
- KPI Card displaying the average of `helpful_reviews`.
- Creation of `developer_answered` column using DAX logic based on whether a developer reply exists.
- Scatterplot comparing average rating by developer response status.

### 🔹 Part 3: App Reviews

- Relationship created between `reviews.app_id` and `apps.id` (Many-to-One).
- Bar Chart of developers vs. total rating.
- Bar Chart of developers vs. average `helpful_reviews` to adjust for review volume.
- Bar Chart of developers' responsiveness (filtered for apps with >500 reviews).

---

## ⚙️ Technical Highlights

- **Data Modeling**: Established relationships between tables to enable cross-table analysis.
- **DAX Measures**: Created calculated columns to enhance review analytics.
- **Visual Design**: Used KPI Cards, Line Charts, Scatterplots, and Bar Charts to provide intuitive and actionable insights.
- **Filtering & Annotation**: Applied data filters and text boxes to improve interpretation.

---

## 📸 Report Snapshots

As .pbix files are not directly shareable due to size constraints, this project includes **8 full-screen screenshots** corresponding to each sub-question across the three report pages.

---

## 🚀 Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Excel (.xlsx) source data**
- **Data Visualization & Modeling**

---

## 📝 Future Enhancements

- Integrate advanced sentiment analysis using review comments.
- Expand KPIs to include install trends or retention metrics if available.
- Automate refreshes with Power BI Service (if source updates regularly).

---

## 📂 Project Files

- `Sprint6_ShopifyAppAnalysis.pdf` – Project screenshots and documentation  
- `.pbix` – Power BI dashboard file (available upon request)

---

## 🙌 Acknowledgments

Thanks to the instructional team and peer reviewers for their feedback during Sprint 6. Special thanks to the open Shopify data community.

---


