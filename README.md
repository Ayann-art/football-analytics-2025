# ⚽ Football Player & Club Analytics 2025
End-to-End Data Analytics Project

---

#  Project Overview

This project presents an end-to-end data analytics pipeline for analyzing football players and clubs for the 2025 season using Python, Excel, and Power BI.

The main objective is to explore player and club performance, market values, positional distributions, disciplinary records, and league-level differences using statistical analysis and data visualization.

The project demonstrates real-world data analytics skills including data collection, cleaning, feature engineering, statistical analysis, and dashboard development.

---

## 🗂️ Project Structure

data/
 ├── raw/
 │    └── Football_Player_Club_Stats_2025_RAW.xlsx
 └── clean/
      └── Football_Player_Club_Stats_2025_CLEAN.xlsx

notebooks/
 └── Player_stats.ipynb

dashboard/
 ├── Football_Player_Club_Stats_2025_powerbi.pbix
 ├── page1.png
 ├── page2.png
 ├── page3.png
 ├── page4.png
 ├── page5.png
 ├── page6.png
 └── page7.png


## 📊 Dataset

Two versions of the dataset are provided:

Raw dataset:  
data/raw/Football_Player_Club_Stats_2025_RAW.xlsx  

Clean dataset:  
data/clean/Football_Player_Club_Stats_2025_CLEAN.xlsx  

The raw dataset was manually collected and structured.  
The clean dataset was produced after preprocessing in Python.

Main attributes include:

- Player Name  
- Age  
- Position  
- Club  
- League  
- Market Value  
- Appearances  
- Goals  
- Assists  
- Minutes Played  
- Yellow Cards  
- Red Cards  


##  Data Cleaning & Preparation (Python)

Data preprocessing steps:

- Handling missing values  
- Converting data types  
- Removing invalid symbols and characters  
- Outlier detection  
- Z-score analysis  
- Quantile-based analysis  
- Feature engineering  
- Correlation analysis  
- Distribution and skewness analysis  


##  Exploratory Data Analysis (EDA)

The following analyses were performed:

- Player performance distributions  
- Market value distributions  
- Positional comparisons  
- League-level comparisons  
- Correlation between numerical variables  
- Detection of extreme values (outliers)  
- Visualization using boxplots, histograms, and scatter plots  


##  Statistical Analysis

The notebook includes:

- Hypothesis testing  
- Z-score calculations  
- Correlation testing  
- Distribution analysis  
- Feature engineering for performance metrics  

These analyses help identify meaningful relationships between performance indicators.

## Power BI Dashboard

Power BI file:  
dashboard/Football_Player_Club_Stats_2025_powerbi.pbix  

Page 1 – Club Value Overview
This page provides a high-level overview of club market values across selected leagues.
Compares total club values.Highlights value differences between leagues and clubs.
Enables quick identification of financially strong teams.
Purpose: To understand how market value is distributed among clubs

![Page1](dashboard/Page1.png)

Page 2 – Player Value Decomposition
This page explores how total player market value is distributed by:
Position
Nationality
Age
Purpose: To identify which player characteristics contribute most to overall market value.

![Page2](dashboard/Page2.png)

Page 3 – Club Profile Analysis
This page focuses on individual club profiles.
Displays key club information.
Shows squad composition and position distribution.
Presents basic historical and infrastructure indicators.
Purpose: To evaluate clubs from a structural perspective.

![Page3](dashboard/Page3.png)

Page 4– Player Profile Analysis
This page provides a player-level overview.
Displays personal, physical, and performance-related attributes.
Shows contribution to squad and match involvement.
Includes disciplinary and injury indicators.
Purpose: To analyze players holistically using multiple performance dimensions

![Page4](dashboard/Page4.png)

Page 5 – League Composition
This page analyzes overall league structure.
Domestic vs foreign player distribution.
Position breakdown.
Nationality diversity.
Purpose: To understand squad composition patterns at league level.

![Page5](dashboard/Page5.png)
Page 6 – Global Player Distribution
This page visualizes player nationalities on a world map.
Shows geographic distribution of players.
Supports filtering by team and league.
Purpose: To explore international diversity of players.

![Page6](dashboard/Page6.png)

Page 7 – Contract Timeline Analysis
This page analyzes player contract expiration periods.
Displays contract distribution by year.
Includes position-based segmentation.
Purpose: To support long-term squad planning and contract management.

![Page7](dashboard/Page7.png)

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Excel  
- Power BI  

## 🎯 Project Objectives

- Build a structured football dataset  
- Clean and preprocess real-world data  
- Perform statistical and exploratory analysis  
- Create meaningful visualizations  
- Develop interactive dashboards  
- Demonstrate end-to-end data analytics skills  

## 👤 Author

Ayan

