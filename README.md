# Live Air Quality Monitoring Dashboard (Power BI)

## Project Overview
This project is a Power BI dashboard built to analyze live air quality
(AQI & PM2.5) data across monitoring stations in Delhi.

The dashboard uses a public API as its data source, allowing it to refresh
automatically without relying on static CSV files.

## Data Source
Live / frequently updated air quality data retrieved through a public API.
API keys and authentication details are not shared for security reasons.

## Dashboard Pages

### 1. Overview
- Average PM2.5, Maximum AQI, total monitoring stations
- AQI category distribution (Good → Severe)
- City-wide pollution map with AQI severity
- Top 5 most polluted stations

### 2. Station-Level Analysis
- Station name slicer for interactive filtering
- Average AQI by station
- Top 5 cleanest stations
- AQI category distribution by station

## Tools & Technologies
- Power BI Desktop
- Live API-based data source
- Data modeling
- Basic DAX measures

## What I Learned
- Working with APIs in Power BI
- Handling live / dynamic data
- Data modeling and DAX basics
- Designing insight-driven dashboards

## Project Files
- `Live_Air_Quality_Dashboard.pbix` – Power BI dashboard file
- `screenshots/` – Dashboard preview images

## Note
GitHub does not support previewing `.pbix` files.
Please refer to the screenshots for dashboard visuals.
