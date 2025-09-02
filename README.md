 
# Zomato Restaurants Analysis using Excel, SQL & Power BI

## 📌 Project Overview

This project analyzes the **Zomato Global Restaurant Dataset** using **Excel, SQL, and Power BI** to uncover insights on restaurant distribution, customer ratings, pricing, services, and cuisine patterns.
The workflow integrates **data cleaning (Excel), SQL queries for aggregation, and Power BI dashboards** to deliver interactive business intelligence on restaurant industry trends.

## 🎯 Objectives

* Build a **country map table** to link country codes with names.
* Build a **calendar table** from `Datekey_Opening` with attributes: Year, MonthNo, MonthName, Quarter (Q1–Q4), YearMonth (YYYY-MMM), WeekdayNo, WeekdayName, FinancialMonth (April–March), and FinancialQuarter.
* Find the **number of restaurants by city and country**.
* Analyze **restaurant opening trends** by year, quarter, and month.
* Count restaurants by **average rating bands**.
* Create **price range buckets** and calculate restaurant distribution per bucket.
* Calculate the **percentage of restaurants with table booking and online delivery**.
* Develop charts based on **cuisines, city, ratings, and services**.

---

## 🛠 Tools & Technologies

* **Excel** – Data cleaning, ETL workflows, and aggregation.
* **SQL** – Querying, aggregation, and transformation.
* **Power BI** – Interactive dashboards, visual analytics, and storytelling.

---

## 📂 Excel Implementation

* **SUMIFS / COUNTIFS** – to count restaurants based on criteria (ratings, services).
* **PivotTables & PivotCharts** – to summarize openings, cuisines, and service adoption.
* **Conditional Formatting** – to highlight outliers and key insights.
* **VLOOKUP & INDEX-MATCH** – to merge country codes and dimension tables.
* **DATE & YEAR functions** – to build the **calendar table**.
* **Report Connections** – linking multiple PivotTables & charts to a single slicer for dynamic filtering.

---

## 🗄️ SQL Implementation

* **SELECT / FROM / WHERE** – to retrieve and filter data.
* **GROUP BY / ORDER BY / HAVING** – for aggregation and trend analysis.
* **Window Functions** (`ROW_NUMBER`, `RANK`, `DENSE_RANK`) – to rank cuisines, cities, and high-rated restaurants.
* **Date Functions** (`DATEADD`, `DATEDIFF`, `DATEPART`) – to extract time-based insights (yearly, quarterly, monthly openings).

---

## 📊 Power BI Implementation

* **Data Modeling** – created relationships between fact and dimension tables.
* **DAX Measures** – for dynamic KPIs (average rating, % restaurants with booking/delivery).
* **Visualizations** – bar charts, maps, rating distributions, price segmentation, cuisine breakdown.
* **Slicers & Filters** – enabled dynamic filtering by **country, city, cuisine, and time period**.
* **Drill-through Functionality** – to navigate between country-level, city-level, and cuisine-level insights.

---

## 🔑 Key Results & Insights

* Only **12.1% of restaurants offer table booking** and **25.7% support online delivery**, with just **0.35% delivering in real-time**.
* Global **average rating = 2.89/5**, with median votes at **23** and 90th percentile votes at **388**.
* **Indian, Chinese, and Italian cuisines dominate (\~40%)**, showing concentrated demand.
* **Top 10 cities host \~45% of restaurants**, while most countries have limited representation.
* Built an **interactive Power BI dashboard** to explore restaurant openings, cuisines, and service adoption trends.

--

## 🚀 Key Learnings

* Practical application of **Excel ETL workflows, SQL window functions, and DAX in Power BI**.
* Hands-on experience in **data modeling, temporal trend analysis, and BI storytelling**.
* Developed a reusable framework for **end-to-end data analysis and visualization projects**.
 
Would you like me to also create a **`📂 Project Structure` section** (with folders like `data/`, `sql/`, `excel/`, `dashboard/`) so your repo looks even more polished?
