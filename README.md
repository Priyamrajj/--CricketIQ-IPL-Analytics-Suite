# IPL Data Analytics Project: Player & Team Performance Dashboard

## Overview

*IPL Data Analytics* is a data analytics project analyzing player performances, team statistics, match outcomes, and venue impacts across IPL seasons. The project leverages Python for data preprocessing, MySQL for querying and advanced analysis, and Power BI for interactive visualizations, delivering actionable cricket insights for analysts and fans.

***

## Table of Contents

- [Project Structure](#project-structure)  
- [Dataset Description](#dataset-description)  
- [Analytical Workflow](#analytical-workflow)  
- [Key Insights](#key-insights)  
- [How to Use](#how-to-use)  
- [Technologies Used](#technologies-used)  
- [Author](#author)  

***

## Project Structure

📁 ipl-data-analytics/  
├── data/  
│   ├── deliveries.csv  
├── sql/  
│   ├── team_performance.sql  
│   ├── player_analysis.sql  
│   ├── toss_impact.sql  
├── python/  
│   ├── data_cleaning.py  
│   ├── exploratory_analysis.py  
│   ├── export_to_sql.py  
├── powerbi/  
│   ├── IPL_dashboard.pbix  
├── visuals/  
│   ├── dashboard_summary.png  
└── README.md  

***

## Dataset Description

- *deliveries.csv:*  
  - Ball-by-ball IPL data with columns like match_id, over, ball, batsman, bowler, runs, extras, wickets.

***

## Analytical Workflow

1. *Data Collection & Cleaning (Python)*  
   - Load and combine datasets.  
   - Handle missing and inconsistent data.  
   - Create calculated fields such as strike rates and economy rates.

2. *Data Analysis (MySQL)*  
   - Import cleaned data into SQL database.  
   - Run queries to analyze team performances, player statistics, venue-wise results, and toss impact.

3. *Visualization (Power BI)*  
   - Import database query results or cleaned CSVs.  
   - Build interactive dashboards with key metrics like top performers, win-loss ratios, phase-wise scores, and toss impacts.

4. *Reporting*  
   - Export dashboard as `.pbix` file and static visuals for sharing insights.

***

## Key Insights

- Certain players consistently excel across multiple seasons.  
- Toss winners tend to have higher win probabilities.  
- Teams show distinct performance trends based on venues.  
- Critical phases like powerplay and death overs have significant match influence.

***

## How to Use

1. Clone or download this repository.  
2. Explore raw data in the `data/` folder.  
3. Run Python scripts in the `python/` folder for data preparation and cleaning.  
4. Load the processed data into your SQL database and execute queries from `sql/`.  
5. Open `IPL_dashboard.pbix` in Power BI for interactive data exploration.  
6. View sample visuals in the `visuals/` folder.

***

## Technologies Used

- Python (Pandas, NumPy)  
- MySQL  
- Power BI  

***

## Author

- *Priyamraj*  

***

*This project provides a complete IPL analytics workflow combining data engineering, statistical analysis, and visualization to gain actionable insights into cricket performances.*
