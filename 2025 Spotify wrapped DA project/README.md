# Spotify Wrapped 2025 Analysis

## Project Overview
An in-depth analysis of my personal music streaming habits spanning the entire year of 2025. This project moves beyond the standard "Spotify Wrapped" summary to uncover deeper behavioral trends, such as peak listening hours, temporal habits, and artist discovery rates.

The goal was to analyze raw streaming history in order to understand listening habits and evolution through the year using **Excel** for data processing and **Power BI** for interactive storytelling.

## 📂 File Structure
* **`2025 Spotify Streaming Report Final Version.pdf`**: A static, high-quality export of the final report.
* **`2025 Spotify Streaming Dashboard + Report.pbix`**: The interactive Power BI dashboard and report source file.
* **`2025 Spotify streaming DA project.xlsx`**: Contains the cleaned and processed Excel datasets alongside pivot tables for analysis.
* **`Report & Dashboard Images/`**: JPGs of the dashboard and report pages.
* **`Resources/`**: Images and icons used in the report.

## 🛠️ Tools & Technologies
* **Data Processing:** Excel (Power Query, Pivot Tables)
* **Visualization:** Power BI (DAX Measures, Interactive Dashboard)
* **Data Source:** Personal Spotify Data Download (JSON format converted to CSV)

## ⚙️ Methodology

### 1. Data Collection & Preparation
* Requested raw streaming history (JSON) directly from Spotify's privacy portal.
* Converted complex JSON hierarchies into flat CSV format for analysis.
* Imported data into **Excel** for initial inspection.

### 2. Data Cleaning & Transformation (Excel)
* **Date & Time Parsing:** Split timestamp columns to isolate "Listening Hour," "Day of Week," "Month," etc, for temporal analysis.
* **Data Enrichment:** Used `XLOOKUP` to merge supplementary artist data (Genres) into the main streaming table.
* **Quality Control:** Filtered out streams with `< 30 seconds` duration and "unknown" artist/tarck names to ensure analysis focused on intentional listening.

### 3. Visualization (Power BI)
* Built a multi-page interactive report focusing on:
    * **Top Artists & Songs:** Ranked by hours played.
    * **Temporal Trends:** Heatmaps showing listening intensity by hour and day.


## 📸 Dashboard Preview
![Dashboard Screenshot](Report_&_Dashboard_Images/Dashboard.jpg)
*(Note: Download the .pbix file to interact with the full dashboard)*

---
*Created by Moses Noah - [Linkedin](https://www.linkedin.com/in/moses-noah-020432234/?originalSubdomain=ng)*
