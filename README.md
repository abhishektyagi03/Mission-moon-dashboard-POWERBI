# 🌙 Mission Moon Analysis Dashboard | Power BI

An interactive **Power BI Mission Moon Analysis Dashboard** created to explore lunar mission history, mission outcomes, launch success and failure patterns, participating countries, and mission activity across different years through KPI cards and dynamic visualizations.

## 📌 Dashboard Preview

![Mission Moon Dashboard](Dashboard/mission_moon_dashboard.png)

## 🎯 Project Objective

The objective of this project is to transform historical moon mission data into an interactive business intelligence dashboard that provides a clear overview of mission outcomes, launch activity, countries, and performance patterns over time.

The dashboard helps users quickly understand how lunar missions performed, which countries launched the most missions, how outcomes are distributed, and how mission activity changed across the selected period.

## 📈 Key KPIs

The dashboard is designed around mission-focused indicators such as:

* 🚀 **Total Moon Missions**
* ✅ **Successful Missions**
* ❌ **Failed Missions**
* 🌍 **Mission-Launching Countries**
* 📅 **Mission Activity Across Years**
* 📊 **Mission Outcome Distribution**

> KPI values depend on the underlying dataset and active year filters. The dashboard screenshot shows a historical period from **1958 to 2023**.

## 🎛️ Dashboard Filters

The dashboard includes a **year-range timeline/filter** that allows users to explore moon mission activity across the selected historical period.

Users can use the year selection to compare mission outcomes and launch activity between different periods.

## 📊 Dashboard Features

* Mission outcome analysis
* Successful and failed mission comparison
* Mission activity by year
* Country-level moon mission analysis
* Outcome distribution analysis
* Mission outcome category comparison
* Historical timeline filtering
* KPI-based mission monitoring
* Interactive Power BI filtering
* Visual exploration of lunar mission history

## 📊 Visualizations Used

### 1. Distribution of Mission Outcomes

A donut chart showing the proportion of different mission outcomes, including successful missions and various failure or unsuccessful outcome categories.

### 2. Mission Outcome Comparison

A column chart comparing the count of missions across outcome categories. This helps identify the most common mission results.

### 3. Missions by Countries

A line/area-style visualization showing the number of moon missions launched by different countries. It highlights countries with greater historical mission activity.

### 4. Year Range Analysis

A timeline filter covering the historical period shown in the dashboard, from **1958 to 2023**, allowing users to focus on specific years or periods.

### 5. Historical Mission Activity

The dashboard combines country and time-based analysis to reveal changes in lunar exploration activity over the decades.

## 💡 Analytical Questions Answered

This dashboard can help answer questions such as:

* How many moon missions were recorded in the dataset?
* How are mission outcomes distributed?
* How many missions were successful compared with unsuccessful missions?
* Which countries launched the highest number of moon missions?
* How did lunar mission activity change over time?
* Which outcome categories occur most frequently?
* During which periods was moon exploration most active?
* How does the mission outcome mix change when the year range is filtered?
* Which countries have the strongest historical presence in lunar exploration?

## 🔎 Key Insights

Based on the dashboard displayed:

* The dashboard covers moon mission activity across a historical period beginning in **1958** and extending to **2023**.
* **Successful** missions form the largest visible portion of the mission-outcome distribution.
* The outcome analysis also includes categories such as **Launch Failure, Spacecraft Failure, Operational, Partial Failure, and En Route**.
* The country-level visualization shows that lunar mission activity is concentrated among a smaller group of countries, with some countries contributing substantially more missions than others.
* The timeline makes it possible to analyze how lunar exploration activity changed across different decades.
* Outcome comparison provides a quick way to evaluate the balance between successful and unsuccessful missions.

> These observations are based on the visible dashboard and should be validated against the underlying dataset before being used for formal research or reporting.

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Cleaning & Transformation**
* **Data Visualization**
* **Business Intelligence**
* **Exploratory Data Analysis**

## 🔄 Project Workflow

```text
Raw Moon Mission Data
        ↓
Data Cleaning & Transformation
        ↓
Data Modeling
        ↓
DAX Measures / Calculations
        ↓
KPI Development
        ↓
Interactive Visualizations
        ↓
Mission Moon Analysis Dashboard
```

## 🧹 Data Preparation

The mission dataset can be prepared using **Power Query** before creating the dashboard.

Typical preparation steps include:

* Removing unnecessary fields
* Handling missing values
* Correcting data types
* Cleaning mission outcome values
* Standardizing country names
* Preparing year fields for time-based analysis
* Creating calculated columns or measures where required
* Validating mission outcome categories

## 🧮 Key Metrics

The project focuses on metrics such as:

```text
Total Missions
Successful Missions
Failed / Unsuccessful Missions
Mission Outcomes
Missions by Country
Missions by Year
Outcome Distribution
Success and Failure Comparison
Country Contribution
Historical Mission Activity
```

## 📂 Repository Structure

```text
Mission-Moon-Analysis/
│
├── 📊 Mission_Moon_Analysis.pbix
├── 📁 Dataset/
│   └── moon_mission_data.csv
├── 🖼️ Dashboard/
│   └── mission_moon_dashboard.png
└── 📄 README.md
```

> Update the file names above if your actual repository uses different names.

## 🚀 How to Use

1. Clone or download this repository.
2. Install **Microsoft Power BI Desktop**.
3. Open the `.pbix` project file.
4. If required, update the dataset path in Power Query.
5. Click **Refresh** to load the latest data.
6. Use the year-range filter to explore different historical periods.
7. Interact with the outcome and country visuals to perform deeper mission analysis.

## 📚 Skills Demonstrated

`Power BI` · `Data Analytics` · `Power Query` · `DAX` · `Data Modeling` · `KPI Analysis` · `Data Visualization` · `Business Intelligence` · `Exploratory Data Analysis` · `Historical Trend Analysis` · `Dashboard Design`

## 👨‍💻 Author

**Abhishek Tyagi**
MCA | Aspiring Data Scientist | Data Analytics Enthusiast

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ **Star** and sharing your feedback.

---

### 🏷️ Tags

`Power BI` `Moon Mission` `Space Data` `Data Analytics` `Business Intelligence` `DAX` `Power Query` `Dashboard` `Data Visualization` `Mission Analysis` `Historical Data` `Data Analyst` `Data Science`
