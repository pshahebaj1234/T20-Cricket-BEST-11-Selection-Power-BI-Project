# 🏏 **T20 Cricket – Best 11 Selection (Power BI Project)**

This project builds a **data-driven T20 Best XI team** using scraped cricket data, Power Query transformations, and advanced DAX measures visualized in Power BI.

---

## 📌 **Project Overview**

The objective is to create an end-to-end workflow:

* 🕸️ Web scraping match & player data
* 🧹 Cleaning & processing raw CSV/JSON
* 🔄 Power Query transformations
* 📊 Power BI dashboard with KPIs
* 🏆 Automatic Best XI player selection

Player roles analyzed:

* Openers
* Middle Order / Anchors
* Finishers
* All-rounders
* Specialist Fast Bowlers

---

## 📂 **Repository Structure**

```
Cricket-Best-11-PowerBI/
│
├── t20_csv_files/
│   ├── dim_match_summary.csv
│   ├── dim_players.csv
│   ├── dim_players_no_images.csv
│   ├── fact_batting_summary.csv
│   └── fact_bowling_summary.csv
│
├── t20_data_preprocessing/
│   ├── cleaned_dim_players.csv
│   ├── cleaned_match_summary.csv
│   └── cleaned_fact_tables.csv
│
├── t20_json_files/
│   ├── inning1.json
│   ├── inning2.json
│   └── match_details.json
│
├── web_scrapping_codes/
│   ├── scraping_players.py
│   ├── scraping_matches.py
│   └── utils.py
│
├── Codebasics-Cricket-Best-11.pbix
├── t20_cric_1_power_query.pbix
├── DAX-Measures-and-Calculated-Columns.xlsx
└── README.md
```

---

## 📁 **Folder Descriptions**

| Folder / File                                | Description                              |
| -------------------------------------------- | ---------------------------------------- |
| **t20_csv_files/**                           | Raw scraped match & player CSV datasets  |
| **t20_json_files/**                          | Raw JSON match data from Cricinfo        |
| **t20_data_preprocessing/**                  | Cleaned datasets used in Power BI        |
| **web_scrapping_codes/**                     | Python scripts for scraping cricket data |
| **t20_cric_1_power_query.pbix**              | Power Query preprocessing file           |
| **Codebasics-Cricket-Best-11.pbix**          | Final dashboard file                     |
| **DAX-Measures-and-Calculated-Columns.xlsx** | All DAX logic used                       |

---

## 📊 **Dashboard Features**

### 🔹 Role-based filtering

* Openers
* Anchors
* Finishers
* All-rounders
* Fast bowlers

### 🔹 KPI metrics

* Batting Avg
* Strike Rate
* Boundary %
* Balls Faced
* Economy Rate
* Dot Ball %
* Bowling Strike Rate

### 🔹 Player comparison visuals

### 🔹 Tooltip-based player cards

### 🔹 Auto-selected Best XI

---

## 🧮 **Sample DAX Measures**

```DAX
Batting Average = DIVIDE([Total Runs], [Innings Batted])

Strike Rate = DIVIDE([Total Runs], [Balls Faced]) * 100

Bowling Economy = DIVIDE([Runs Conceded], [Overs Bowled])

Dot Ball % = DIVIDE([Dot Balls], [Balls Bowled]) * 100
```

Full list in:
**DAX-Measures-and-Calculated-Columns.xlsx**

---

## 🚀 **How to Run**

1. Clone the repo
2. Open **Codebasics-Cricket-Best-11.pbix** in Power BI Desktop
3. Ensure folder paths remain the same
4. Click **Refresh**
5. Explore the dashboard

---

## 🛠️ **Tech Stack**

* Power BI Desktop
* Power Query (M Language)
* DAX
* Python (Scraping)
* CSV / JSON / Excel

---

## 📬 **Contact**

**Shahebaj Pathan**
