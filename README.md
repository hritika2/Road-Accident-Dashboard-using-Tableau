# 🚦 Road-Accident-Dashboard-using-Tableau
   An end-to-end analytical Tableau project built using ~660,000 accident records from Kaggle (dummy/demo dataset).
   The project focuses on KPI development, dynamic parameters, monthly trends, and interactive visual exploration of accident patterns across four years.

# Dataset Overview
  - Source: Kaggle (dummy/demo dataset; not real-time/governmental)
  - Size: ~660,000 records
  - Fields Used: 14 primary fields
  - Timeframe: 2019–2022 (dates modified)
  - Format: CSV, imported as a Tableau extract for faster performance
  - Data Prep: Cleaned, validated, and assigned correct data types (including geographic types for lat/long)

# Dashboard Features
  ### Filters
   - Current Year
   - Previous Year
   - Accident Severity: Fatal, Serious, Slight

   ### KPIs

   
   - Total Accidents
   - Total Casualties
   - Fatal Casualties
   - Serious Casualties
   - Slight Casualties

   ### Visualizations

   - Bar chart: Casualties by Road Type
   - Donut charts: Weather Condition, Road Surface
   - Map chart: Casualties by Location
   - Vehicle Type breakdown (horizontal section)
   - Monthly trends with sparklines comparing current vs previous year
   - Dynamic color changes based on severity filter
   - Interactive action filters to drill down by:
   - Vehicle type
   - Weather condition
   - Road type, etc.
