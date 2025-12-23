# Terrorism-Analysis-Dashboard
##🧠 Terrorism Insights & Analysis Dashboard (Power BI)
📊 Global & India Terrorism Data Visualization | Interactive Analytics Dashboard
📌 Project Overview

This project focuses on analyzing historical terrorism data using Microsoft Power BI to uncover meaningful insights related to global terrorism trends, high-risk regions, attack patterns, and human impact.

The dashboard is divided into two analytical perspectives:

🌍 Global Terrorism Dashboard – Provides a worldwide overview of terrorism incidents

🇮🇳 Terrorism in India Dashboard – Offers a focused and detailed analysis of terrorism within India

The purpose of this project is to convert raw data into interactive, visual, and decision-support insights using modern data analytics techniques.

##🎯 Objectives

✔️ Analyze global terrorism trends over time
✔️ Identify the most affected countries, regions, and hotspots
✔️ Understand attack patterns, weapon types, and target distribution
✔️ Evaluate casualties and severity of attacks
✔️ Provide a focused national-level analysis for India
✔️ Demonstrate effective use of Power BI for analytical storytelling

##🗂️ Dataset Description

The dataset contains historical terrorism incident records across multiple countries.

Key Columns
📅 Date, Year, Month
🌍 Country, Region, State, City
💣 Attack Type, Weapon Type, Target Type
🧠 Terrorist Group
⚠️ Killed, Wounded, Total Casualties (Calculated)
📍 Latitude & Longitude (for maps)
Each row represents a single terrorist incident.

##🧹 Data Preprocessing
Performed in Power Query:
Removed irrelevant and duplicate columns
Handled missing values
Standardized categorical values
Converted data types
Removed invalid coordinates
Created calculated fields:
Casualties = Killed + Wounded
Extracted Year, Month, Quarter

##🏗️ Data Modeling
Star Schema implemented for better performance:
📌 Fact Table
Fact_Incidents
📌 Dimension Tables
Dim_Date
Dim_Country
Dim_AttackType
Dim_TargetType
Dim_WeaponType
Dim_Group

Relationships configured as one-to-many with directional filtering.

#📊 Dashboard Visuals
##🌍 Global Terrorism Dashboard Includes

✔ KPI Cards
✔ Global Heat Map
✔ Year-wise Trend Line Chart
✔ Attack Type Donut Chart
✔ Most Affected Countries Bar Chart
✔ Interactive Slicers

##🇮🇳 Terrorism in India Dashboard Includes

✔ India-Specific KPI Cards
✔ India Heat Map
✔ Year-wise Trend Chart
✔ Top Affected States / Cities
✔ Attack Type Distribution
✔ State & Year Slicers

##🧬 Key Insights

Terrorism incidents are regionally concentrated rather than evenly spread
South Asia & Middle East show significantly high activity
Armed assaults & bombings are most common attack types
Few countries contribute to majority of global incident
In India, certain states consistently appear as hotspots
Casualties vary significantly by attack type

##🛠️ Tech Stack
Power BI
Power Query
DAX
Data Modeling (Star Schema)

##🚀 Future Scope
🔄 Real-time terrorism data integration
🤖 Predictive analytics & forecasting using ML
🗺️ Advanced geospatial clustering & heat intensity
📊 Cross-country comparative analysis
📈 Enhanced interactive features & detailed drilldowns

##✅ Conclusion
This project demonstrates how terrorism data can be effectively analyzed using Power BI to produce insightful, interactive dashboards. It not only helps visualize historical terrorism patterns but also supports better situational understanding and potential decision-making for researchers, analysts, and policymakers.
