**README.md**

# 🌐 Airlines Occupancy & Profitability Analysis Project

This project analyzes airline operations using SQL and Python (pandas, matplotlib, seaborn) on the `travel.sqlite` database. The objective is to uncover insights that can help improve occupancy rates, optimize fleet usage, and enhance revenue generation for flights.
## 📌 Project Background
The airline operates a variety of aircraft, providing domestic and regional services. Due to rising fuel costs, stricter regulations, increased labor expenses, and market challenges, the company seeks to improve profitability by analyzing operational data. The focus is to optimize occupancy rates and revenue per seat using the provided database.


## 📄 Dataset Overview

**Source:** `travel.sqlite`
**Dataset Link:** [Dataset](https://github.com/Gourab-Talukder/Airline_performance_analytics_using_Sqlite_and_Python/blob/202daf7a5860f0a057dd9bdf70ee03968579a8f1/travel.zip)

| Table Name        | Description                             |
| ----------------- | --------------------------------------- |
| `aircrafts_data`  | Aircraft type, model, and range         |
| `airports_data`   | Airport details like city, location     |
| `boarding_passes` | Boarding and seat assignment records    |
| `bookings`        | Booking reference, date, and revenue    |
| `flights`         | Flight schedules, routes, aircraft used |
| `seats`           | Seat number and fare class per aircraft |
| `ticket_flights`  | Ticket price and flight linkage         |
| `tickets`         | Ticket and passenger reference data     |

## 🧰 Tools Used

* SQLite + SQL queries
* Python (pandas, matplotlib, seaborn)
* Jupyter Notebook

## 🔎 Key Analyses

* Flight status distribution and delays
* Ticket revenue aggregation
* Monthly booking trends
* Flight occupancy rates
* Aircraft-wise and route-wise profitability

## 🚀 Goals

* Identify low occupancy flights
* Improve aircraft and route utilization
* Recommend dynamic pricing opportunities
* Discover booking seasonality trends

## 📚 Files Included

* `analysis_report.md`: Full detailed project report with SQL and Python logic.
* `queries/`: Folder containing reusable SQL queries.
* `notebooks/`: Jupyter notebook version of the full analysis.
* `visuals/`: All generated plots and charts.

---
