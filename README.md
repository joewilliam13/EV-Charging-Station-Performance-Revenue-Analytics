# EV-Charging-Station-Performance-Revenue-Analytics
Interactive Power BI dashboard for analyzing EV charging station performance, revenue, energy consumption, session behavior, and geographical performance.
## 📊 Project Overview

This project analyzes EV charging session data and converts it into an interactive business intelligence dashboard using Power BI.

The dashboard helps identify high- and low-performing charging stations, understand charging behavior, monitor revenue trends, and compare performance across cities and charger types.

## 🎯 Business Objectives

- Monitor charging station performance
- Analyze revenue generated from completed charging sessions
- Track energy consumption and charging duration
- Compare station and city-level performance
- Analyze charger, vehicle, and customer usage
- Identify high- and low-performing stations
- Support revenue optimization and capacity planning
- Support future charging station expansion decisions

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Excel / CSV
- Data Cleaning
- Data Modeling
- Data Visualization
- Time-Series Analysis

## Dataset
-<a href="https://github.com/joewilliam13/EV-Charging-Station-Performance-Revenue-Analytics/blob/main/EV_Charging_Station.csv"> Dataset</a>
## 📑 Dashboard Pages

### 1. Overview

Provides a high-level summary of EV charging operations and revenue performance.

**Key KPIs:**
- Total Revenue
- Completed Sessions
- Total Energy
- Average Revenue per Session
- Average Charging Duration
- Station Utilization
- Revenue MoM Growth

**Key Visuals:**
- Monthly Revenue Trend
- Top 10 Charging Stations by Revenue
- Sessions by Charger Type
- Energy Consumption by Vehicle Type

---

### 2. Station Analysis

Analyzes the performance of individual charging stations.

**Key KPIs:**
- Total Revenue
- Completed Sessions
- Total Energy
- Average Revenue per Session

**Key Visuals:**
- Revenue by Charging Station
- Charging Sessions by Station
- Energy Consumption by Charging Station
- Station Utilization by Charging Station
- Revenue vs Energy by Station
- Top & Bottom Performing Stations

---

### 3. Session Analysis

Analyzes charging activity, session status, charging duration, and customer usage.

**Key KPIs:**
- Completed Sessions
- Completion Rate
- Average Charging Duration
- Average Energy per Session

**Key Visuals:**
- Sessions by Session Status
- Sessions by Duration Category
- Charging Sessions Trend
- Sessions by Customer Type

---

### 4. Revenue Analysis

Provides detailed financial performance analysis.

**Key KPIs:**
- Completed Revenue
- Average Revenue per Session
- Revenue per kWh
- Revenue MoM Growth

**Key Visuals:**
- Monthly Revenue Trend
- Revenue by City
- Top 10 Revenue Stations
- Revenue vs Energy

---

### 5. Location Analysis

Analyzes geographical performance and station utilization.

**Key KPIs:**
- Total Stations
- Active Stations
- Total Revenue
- Average Station Utilization

**Key Visuals:**
- Revenue by City / Location
- Sessions by City
- Station Utilization by City
- Geographic Revenue Visualization
## 🧹 Data Preparation

Data preparation and transformation were performed using Power Query.

Key steps included:

- Promoting headers
- Data type validation
- Removing duplicate records
- Filtering invalid records
- Cleaning text fields
- Trimming text values
- Validating numerical columns
- Creating Duration Category
- Creating Energy Category
- Preparing the data for DAX analysis

## 🗓️ Data Model

The project uses a simple star-schema approach with:

- `EV_Charging_Station` – Main fact table
- `Calender` – Date dimension table

## 🔍 Power BI Features Used

- Power Query for data cleaning and transformation
- DAX-based calculations
- Calendar table and time-intelligence analysis
- Interactive slicers
- Slicer synchronization across report pages
- Cross-filtering
- Top N analysis
- Conditional formatting
- Page navigation
- KPI cards
- Bar charts
- Column charts
- Line charts
- Donut charts
- Scatter plots
- Map visualization
'
##  Business Insights

The dashboard helps businesses identify:

- High-performing and low-performing charging stations
- Revenue trends across months and cities
- Charger types with higher session demand
- Vehicle types with higher energy consumption
- Customer usage patterns
- Stations with higher utilization
- Relationship between energy consumption and revenue
- Locations with strong revenue potential
- Opportunities for capacity planning and future station expansion

## Dashboard Preview
### Overview
-<a href="https://github.com/joewilliam13/EV-Charging-Station-Performance-Revenue-Analytics/blob/main/screenshots/Page_1.png">Dashboard</a>
### Station Analysis
-<a href="https://github.com/joewilliam13/EV-Charging-Station-Performance-Revenue-Analytics/blob/main/screenshots/Page_2.png">Dashboard</a>
### Session Analysis
-<a href="https://github.com/joewilliam13/EV-Charging-Station-Performance-Revenue-Analytics/blob/main/screenshots/Page_3.png">Dashboard</a>
### Revenue Analysis
-<a href="https://github.com/joewilliam13/EV-Charging-Station-Performance-Revenue-Analytics/blob/main/screenshots/Page_4.png">Dashboard</a>
### Location Analysis
-<a href="https://github.com/joewilliam13/EV-Charging-Station-Performance-Revenue-Analytics/blob/main/screenshots/Page_5.png">Dashboard</a>

## 📌 Project Outcome

This project provides an interactive Power BI solution for monitoring EV charging operations and business performance.

The dashboard enables users to:

- Track revenue and charging activity
- Compare station and city performance
- Understand customer and charging behavior
- Monitor energy consumption and station utilization
- Identify high- and low-performing locations
- Support data-driven business and expansion decisions

## 🎯 Conclusion

This project demonstrates how Power BI can be used to transform EV charging data into meaningful business insights.

The dashboard provides a clear view of revenue, charging sessions, energy consumption, station performance, customer usage, and geographical performance to support data-driven decision-making.
