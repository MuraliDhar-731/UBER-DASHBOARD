# 📊 Uber Operations Dashboard

Interactive Power BI dashboard analysing Uber trip data — fares, driver performance, and demand patterns by location and time. Built as a university group project.

## 🎯 Objective

Transform raw Uber trip data into actionable business intelligence through interactive visualisations helping operations teams understand demand, revenue, and driver performance.

## ✨ Features
- 🗺️ Geo-spatial demand heatmaps by pickup/dropoff location
- 📈 Time-series trend lines — hourly, daily, and weekly patterns
- 💰 Fare analytics — average fares, surge pricing, revenue trends
- 🚗 Driver performance — completion rates, ratings, utilisation
- 🔍 Dynamic filters and slicers for drill-down by date, location, trip type
- 📊 KPI cards for key business metrics at a glance

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Dashboard | Power BI |
| Data Preparation | Python (Pandas, NumPy) |
| Analytics | DAX |
| Data Storage | SQL |
| Visualisation | Power BI Maps, Charts, KPIs |

## 📁 Project Structure

```
Uber-Dashboard/
├── data/
│   ├── raw/                  # Raw Uber trip data
│   └── processed/            # Cleaned data for Power BI
├── scripts/
│   ├── clean_data.py         # Data cleaning pipeline
│   └── transform.py          # Feature engineering
├── dashboard/
│   └── uber_dashboard.pbix   # Power BI dashboard file
└── README.md
```

## 🏗️ Data Pipeline

```
Raw Trip Data → Python Cleaning → Feature Engineering → 
SQL Storage → Power BI Import → DAX Measures → 
Interactive Dashboard
```

## 📊 Key Insights Delivered
- Peak demand hours and locations identified
- Revenue optimisation opportunities surfaced
- Driver utilisation patterns visualised
- Geographic demand distribution mapped

## 🖼️ Dashboard Sections
1. **Overview** — Total trips, revenue, active drivers KPIs
2. **Demand Analysis** — Heatmaps and time-series by location
3. **Fare Analytics** — Pricing trends and surge analysis
4. **Driver Performance** — Ratings, completion rates, utilisation
5. **Filters** — Date range, city, trip type drill-down

---
*Group Project — University of New Haven · M.S. Data Science*
