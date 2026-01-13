# 🎣 NJ Stream Conditions Dashboard (USGS API)

This project is a personal data analytics project built around a hobby of mine: **fly fishing**. Before heading out, I regularly check river conditions such as streamflow and gauge height to determine whether conditions are safe and fishable. This dashboard simplifies that process by pulling **near real-time data from the USGS Water Services API** and presenting current conditions for select rivers in New Jersey.

---

## 📌 Project Overview

The dashboard displays current stream conditions for **three New Jersey rivers**, using publicly available USGS data. The project demonstrates a simple, end-to-end BI workflow:

**USGS API → Power Query (ETL) → Power BI Dashboard**

The focus is on clean data ingestion, repeatable transformations, and clear visual design for quick decision-making.

---

## 🛠️ Tools & Technologies

- **Data Source:** USGS Water Services API  
- **ETL / Data Transformation:** Power Query (M)  
- **Data Modeling & Visualization:** Power BI  
- **Concepts Demonstrated:**
  - API-based data ingestion
  - Power Query transformations and normalization
  - Time-series data handling
  - BI modeling and dashboard design

---

## 📊 Dashboard Features

- Current streamflow and gauge height by river
- Timestamp of the most recent USGS reading
- At-a-glance comparison across rivers
- Clean, minimal layout optimized for fast condition checks

> Note: This dashboard is intended for informational use only and should not be relied upon for safety-critical decisions.

---

## 🎯 Purpose of the Project

This project serves two goals:

1. **Personal Use** – Quickly assess stream conditions before fly fishing outings  
2. **Portfolio Demonstration** – Showcase practical BI skills using a real-world public API

The project mirrors common operational dashboards used in enterprise settings: current-state monitoring, standardized transformations, and refreshable data models.

---

## 🗂️ Repository Structure

```text
/
├── powerquery/           # Power Query (M) scripts for API ingestion and ETL
├── powerbi/              # Power BI dashboard files
├── docs/                 # Notes, references, and diagrams
└── README.md