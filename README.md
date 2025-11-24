# Spotify-Analysis
Spotify Music Analysis Dashboard
(Power BI • Excel • Power Query • DAX)

This project presents an in-depth analysis of Spotify music trends using Power BI, Excel, Power Query, and DAX. The dashboard provides interactive insights into track performance, artist popularity, user engagement patterns, and listening trends over time.

# Project Overview

The primary objective of this project is to analyze Spotify datasets and extract meaningful insights regarding user listening behavior.
Using Excel for preprocessing, Power Query for data transformation, and DAX for modeling and KPIs, the analysis is visualized through a dynamic and interactive Power BI report.

# Features
📥 Data Preparation (Excel + Power Query)

Cleaned and structured raw CSV/Excel files.

Removed inconsistent entries, empty rows, duplicates, and invalid values.

Created relationships between tables (tracks, artists, albums, genres).

Renamed columns, changed data types, and created calculated columns.

Built a star-schema–based model for better performance.

# DAX Measures Used

Custom DAX measures were created for deeper insights, including:

Total Streams

Average Popularity

Year-over-Year Percentage Change

Top Artist/Track Calculations

Weekday vs Weekend Listening Metrics

Quadrant Classification for Popularity vs Engagement

Trend Lines Using Time Intelligence

Time Intelligence functions used:
TOTALYTD(), SAMEPERIODLASTYEAR(), DATEADD(), CALCULATE(), FILTER(), DIVIDE()

# Power BI Dashboard Highlights

Top Artists • Albums • Tracks

Trend Analysis (Monthly/Yearly)

Popularity vs Engagement Scatter Plot (Quadrant View)

Listening Patterns: Weekday vs Weekend

Genre-Based Summary Charts

Dynamic Filters & Slicers

Light and clean UI for better readability

# Project Files
File	Description
spotify_analysis.pbit	Power BI template file used to generate the dashboard
dataset.xlsx (if included)	Cleaned and transformed dataset

(Your uploaded file: spotify_analysis.pbit is already included.)

# How to Use This Dashboard

Download the repository.

Open Power BI Desktop.

Load the file:
spotify_analysis.pbit

Connect it to your dataset (Excel file).

Refresh the model to view insights instantly.

# Technologies Used

Microsoft Power BI – Dashboard creation

Excel – Initial data cleaning and formatting

Power Query (M language) – Data transformation

DAX (Data Analysis Expressions) – Calculations, KPIs, and time-intelligence

💡 Key Insights Identified

Weekend listening activity is significantly different from weekdays.

Popularity distribution shows clear clusters through quadrant analysis.

Artists with consistent performance stand out in year-over-year trends.

Track duration and audio features influence track popularity.

# Dashboard Preview
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/4b2f2688-a11a-4514-846d-bf65bc43a903" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/d6436658-3e77-4da1-b909-4441c7d87657" /> 
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/f8f2c7a3-533d-4e18-8e25-6de81d7ccf5a" />

