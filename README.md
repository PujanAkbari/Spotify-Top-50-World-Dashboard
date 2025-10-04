# Spotify-Data-Analyzer-Dashboard-Power-BI

# 🎧 Spotify Data Analyzer Dashboard (Power BI)

### 📌 Project Summary
**Spotify Data Analyzer Dashboard (Power BI):** 📈 Designed and developed a multi-page, interactive dashboard in **Power BI** to analyze and visualize pre-processed historical song and artist performance data. The dashboard provides music stakeholders (analysts, marketing teams) with a consolidated view of **Key Performance Indicators (KPIs)**, **Trend Analysis**, **Popularity Rankings**, and **Distribution Comparisons** (e.g., Explicit vs. Non-Explicit, Album Type) without requiring any live API connection.

***

## 📌 Business & Problem Overview

### Business Requirement 🎯
Spotify stakeholders (music analysts, playlist managers, and marketing teams) need a consolidated dashboard to monitor song and artist performance across different dimensions. The project delivers three core views: **Overview**, **Artists**, and **Songs**, each providing targeted analytics.

### Problem Statement 🧐
Spotify's raw data is often limited to basic lists and rankings, making it difficult for stakeholders to see historical patterns, compare performance across different track types, and gain quick, actionable insights. This dashboard solves this by:
1.  **Providing Context:** Displaying historical trends (by month/year) for popularity and distinct songs.
2.  **Enabling Comparison:** Visualizing distributions like **Explicit vs. Non-Explicit** and **Album vs. Single**.
3.  **Surfacing Metrics:** Calculating and visualizing key metrics like **Average Popularity** and **Distinct Song Counts**.

***

## ✨ Dashboard Features & Pages

The dashboard is structured into three main pages, each addressing specific analytic needs:

| Page | Key Focus | Core Features |
| :--- | :--- | :--- |
| **Overview** 📊 | High-level KPIs & Trends | Total Songs, Distinct Artists, Avg Popularity, **Monthly Trend Analysis**, Explicit vs. Non-Explicit share, Songs by Album Type. |
| **Artists** 🧑‍🎤 | Artist Performance Deep Dive | **Top Artists by Popularity**, Tracks per Album comparison, detailed artist-level data table (Release Date, Position, Avg Popularity). |
| **Songs** 💿 | Track-Level Analysis & Ranking | **Top Songs by Popularity**, Tracks per Song (Album/Single) distribution, **Total Songs by Artist** ranking (large chart). |

***

## 🛠 Tools & Technologies

* **Power BI Desktop** – For dashboard creation, data modeling, and visualization.
* **Power Query** – Used for data extraction, loading, and transformation (ETL) of the source dataset.
* **DAX (Data Analysis Expressions)** – For creating calculated measures, explicit metrics, and Key Performance Indicators (KPIs).
* **Pre-processed Data Source** – The dashboard operates on a static, prepared dataset (no live API connection required).

***

## 📂 Project Workflow

1.  **Data Source Loading** ➡️
    * Pre-processed music performance data loaded directly into Power BI.
2.  **Data Transformation** 🧼
    * Data cleaned, shaped, and transformed using **Power Query**.
3.  **Data Modeling & DAX** 🔗
    * Relationships created and structured data tables modeled.
    * Calculated metrics (like averages and distributions) applied using **DAX**.
4.  **Visualization** 🎨
    * Used Power BI visuals (cards, line charts, bar charts, slicers) to create an interactive and visually appealing interface that mimics the Spotify brand's dark theme.

***

## 📷 Dashboard Preview

### 1. Overview Page: KPIs and Monthly Trends

![Screenshot of the Overview Page showing KPIs, popularity charts, and song distributions.](Screenshot%202025-10-04%20192042.jpg)

<hr style="border: none; height: 3px; background-color: black;">

### 2. Artists Page: Artist Performance Analysis

![Screenshot of the Artists Page showing top artists, song-by-artist comparisons, and a detailed artist data table.](Screenshot%202025-10-04%20192106.jpg)

<hr style="border: none; height: 3px; background-color: black;">

### 3. Songs Page: Track-Level Popularity and Counts

![Screenshot of the Songs Page showing top songs, distribution of tracks per song, and a graph of total songs by artist.](Screenshot%202025-10-04%20192128.jpg)

<br>

***

## 📁 Repository Contents
-   `/pbix/` → Contains the **Power BI file (`.pbix`)** for this dashboard.
-   `README.md` → Documentation for the project.

***

## 🔮 Future Improvements
-   **Parameterization** ⚙️: Implement date or artist parameters for easier filtering.
-   **Mobile Layout** 📱: Create a mobile-optimized version of the report.
-   **Data Refresh** 🔄: Connect to a cloud-based data source (e.g., Azure SQL, Excel Online) to enable scheduled data refresh in the Power BI Service.

***

## 🎯 Learning Outcomes
-   Mastery of **Power BI Dashboard** design and best practices.
-   Advanced **Power Query** techniques for data shaping.
-   Building complex **DAX** measures for comparative analysis.
-   Designing **user-friendly, visually engaging reports** in a distinct brand theme.

***

## 📜 License
This project is for **educational and personal use**.

***
