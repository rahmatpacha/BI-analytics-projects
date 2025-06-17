# Zuber Taxi Analytics Project

A business intelligence analytics project completed as part of the TripleTen BI Analytics Bootcamp.  
This project focuses on exploring and analyzing trip and weather data for a fictional taxi company, **Zuber**, using SQL queries to generate insights for business decisions.

---

## 🚕 Project Overview

**Goal:**  
To analyze taxi ride data, company performance, and the impact of weather on operations using SQL and data visualization tools.

**Key Topics:**
- Ride volume and company performance on specific dates
- Company segmentation and grouping for targeted analysis
- Integration of external data (weather, neighborhoods)
- Advanced filtering and grouping with SQL logic

---

## 📊 Analytical Tasks & SQL Queries

### 1. Rides Per Company (Nov 15–16, 2017)
- Calculated the number of rides per taxi company for a given period.
- Output: Company name, ride count (`trips_amount`), sorted by ride count.

### 2. Rides for "Yellow" or "Blue" Companies (Nov 1–7, 2017)
- Filtered companies whose names contain "Yellow" or "Blue".
- Aggregated ride counts for these companies during a specific week.

### 3. Grouping Top Companies vs. Others
- Isolated the most popular companies ("Flash Cab" and "Taxi Affiliation Services") and grouped all others as "Other".
- Compared their ride counts for Nov 1–7, 2017.

### 4. Neighborhood Identifier Lookup
- Retrieved the unique identifiers for "O'Hare" and "Loop" neighborhoods to use in further analysis.

### 5. Weather Condition Categorization
- Classified each hour's weather as "Good" or "Bad" based on description (rain/storm).
- Output: Timestamp and weather condition label for each hour.

### 6. Saturday Rides: Loop to O'Hare with Weather Conditions
- Analyzed all Saturday rides starting in the Loop and ending at O'Hare.
- Included ride start time, weather condition at the time, and ride duration.
- Only included rides where weather data was available.

---

## 🗝️ Key Skills Demonstrated

- Complex SQL querying: filtering, aggregation, case logic, and joins.
- Data enrichment by joining ride records with weather and location data.
- Business insight generation for operational and strategic taxi company decisions.
- Preparation of clear and reproducible analytical steps for BI dashboards.

---

## 📝 Project Structure

- `README.md` – Project documentation (this file)
- `Zuber.pdf` – Full report with SQL queries and explanations

---

## 📑 Example SQL Query

```sql
SELECT
    c.company_name,
    COUNT(t.trip_id) AS trips_amount
FROM
    cabs c
INNER JOIN
    trips t ON c.cab_id = t.cab_id
WHERE
    CAST(t.start_ts AS date) BETWEEN '2017-11-15' AND '2017-11-16'
GROUP BY
    c.company_name
ORDER BY
    trips_amount DESC;
