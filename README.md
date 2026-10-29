# 🌾 Global Food Production Trends & Analysis Using Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green?style=for-the-badge)
![CSV](https://img.shields.io/badge/Dataset-CSV-orange?style=for-the-badge)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-purple?style=for-the-badge)
![Period](https://img.shields.io/badge/Period-1961--2021-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

<!-- Visitor Badge -->

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=spsourabh17.global-food-production-power-bi)

---

## 📌 Overview

This project is an **interactive Power BI dashboard** that analyzes **global food production trends** across countries, crops, and years.

It transforms a large historical dataset into clear visual insights, enabling:

* Country-wise and region-wise production analysis
* Long-term trend tracking across six decades
* Crop-to-crop comparison with interactive filters

---

## 🧠 Problem Statement

Global food production is central to food security, economic stability, and sustainable resource management. However, stakeholders struggle to interpret large, scattered datasets on production and supply trends.

This project addresses the problem by:

* Providing a centralized, visual view of food production data
* Making trends, patterns, and anomalies easy to spot
* Enabling drill-down by country, crop, and time period
* Supporting faster, data-driven decisions

---

## 📊 Dataset

| Property | Details |
| --- | --- |
| **File** | `world food production.csv` |
| **Records** | ~11,900 rows |
| **Entities** | 226 countries / regions |
| **Years Covered** | 1961 – 2021 |
| **Metric** | Production in tonnes |

**Crops / products included (22):**
Maize, Rice, Yams, Wheat, Tomatoes, Tea, Sweet Potatoes, Sunflower Seed, Sugar Cane, Soybeans, Rye, Potatoes, Oranges, Dry Peas, Palm Oil, Grapes, Green Coffee, Cocoa Beans, Chicken Meat, Bananas, Avocados, Apples.

---

## 🚀 Core Features

### 📈 KPI Cards

* Total production at a glance
* Crop-level and country-level KPIs that update with filters

### 🗺️ Geographical Analysis

* Interactive map showing production by country
* Country slicer to focus on any single nation

### ⏳ Time-Series Analysis

* Stacked area charts showing production over the years
* Crop-wise contribution to production over time

### 🌽 Crop-Wise Comparison

* Clustered bar charts comparing crops and top producing countries
* Donut charts showing each crop's share of total production

### 🎛️ Interactive Filtering

* Cross-filtering between all visuals
* Click any country or crop to drill into the details

---

## 🏗️ Solution Architecture

```text
CSV Data Source
      │
      ▼
Power Query  ──►  Cleaning, standardizing, handling missing values
      │
      ▼
Data Model   ──►  Relationships between country, year, and production
      │
      ▼
DAX          ──►  Measures and aggregations
      │
      ▼
Power BI Dashboard  ──►  Slicers, filters, drill-through, insights
      │
      ▼
Power BI Service    ──►  Publishing and access control
```

---

## ⚙️ Technology Stack

* **BI Tool:** Microsoft Power BI Desktop
* **Data Transformation:** Power Query (M Language)
* **Calculations:** DAX
* **Data Source:** CSV
* **Documentation:** PDF reports for each project phase

---

## 📂 Project Structure

```bash
Global-Food-Production-Trends-Using-Power-BI-Project/
│
├── 1.Assignment/
│   ├── Assignment no 1.pdf
│   ├── Assignment no 2.pdf
│   └── Assignment no 3.pdf
│
├── 2.Ideation Phase/
│   ├── Empathy Map Canvas.pdf
│   ├── Problem Statement.pdf
│   └── Brainstorming- Idea Generation- Prioritizaation Template.pdf
│
├── 3.Requirements Analytics/
│   ├── Solution Requirements.pdf
│   ├── data flow diagram.pdf
│   ├── Technology Stack.pdf
│   └── Customer Journey Map.pdf
│
├── 4.Project Design Phase/
│   ├── Problem Solution Fit.pdf
│   ├── Proposed Solution.pdf
│   └── Solution Architecture.pdf
│
├── 5.Project Planing Phase/
│   └── Project Planning Template new1.1.pdf
│
├── 6.Project Executable Files/
│   ├── Global Food Production.pbix
│   ├── world food production.csv
│   └── Project Screenshot.jpg
│
├── 7.Functional And Performance Testing/
│   ├── Artificial Intelligence.pdf
│   ├── Machine Learning.pdf
│   └── Salesforce phase.pdf
│
└── 8.Doc and Demo/
    ├── Global_Food_Production.pbix
    └── PowerBI_Video.mp4
```

---

## 🖼️ Dashboard Preview

![Dashboard Screenshot](<6.Project Executable Files/Project Screenshot.jpg>)

---

## 🎬 Demo Video

A walkthrough of the dashboard (about 2.5 minutes) is available in:

```text
8.Doc and Demo/PowerBI_Video.mp4
```

---

## 🖥️ Running the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/spsourabh17/Global-Food-Production-Trends-Using-Power-BI-Project.git
cd Global-Food-Production-Trends-Using-Power-BI-Project
```

### 2️⃣ Install Power BI Desktop

Download the free [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows).

### 3️⃣ Open the Dashboard

Open either of these files in Power BI Desktop:

```text
6.Project Executable Files/Global Food Production.pbix
8.Doc and Demo/Global_Food_Production.pbix
```

### 4️⃣ Refresh Data (if the source path breaks)

1. Go to **Home → Transform data → Data source settings**
2. Click **Change Source**
3. Point it to `6.Project Executable Files/world food production.csv`
4. Click **Refresh**

---

## 🎯 Target Users

* 🏛️ Government & policymakers – food security and sustainability planning
* 🔬 Researchers & analysts – long-term agricultural trend studies
* 💼 Businesses & traders – market and supply insights

---

## 👨‍💻 Author

**Sourabh Patil**

* 🔗 GitHub: [https://github.com/spsourabh17](https://github.com/spsourabh17)
* 💼 LinkedIn: [https://www.linkedin.com/in/sourabh-patil-5242402b7](https://www.linkedin.com/in/sourabh-patil-5242402b7)

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

---
