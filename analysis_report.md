# 📊 Full Airlines Occupancy & Profitability Analysis Report

## Project Summary

A complete data analysis of airline operations using the `travel.sqlite` dataset. The aim is to identify low-performing flights, optimize revenue per seat, and align aircraft deployment to demand patterns using SQL and Python.

## Business Problems Addressed

1. Low seat occupancy rates on multiple routes.
2. Revenue inefficiencies across different aircraft types.
3. Seasonal trends in bookings.
4. Misalignment between pricing and demand.
5. Underperforming routes and inefficient aircraft utilization.

## Key Questions Answered

* How many total flights and what are their status breakdowns?
* What is the total number of passengers and ticket revenue?
* Which routes and aircrafts are most/least profitable?
* How is the occupancy rate distributed across flights?
* What monthly trends can be observed in bookings and revenue?

## Insights Discovered

* Over 25% of flights operate at less than 50% capacity.
* Certain aircraft models consistently underperform in revenue-per-seat.
* Route-level analysis shows that specific corridors bring in most revenue.
* Seasonal spikes observed in March, June, and December.

## Data Metrics Calculated

* Occupancy Rate = Boarded Passengers / Seat Capacity
* Revenue per Seat = Total Revenue / Seat Capacity
* Revenue per Passenger = Total Revenue / Boarded Passengers
* Avg Revenue per Flight per Aircraft Type
* Route Profitability = Avg Revenue + Avg Occupancy

## Visuals Included

* Revenue trend over months
* Occupancy rate distribution
* Aircraft model efficiency (bar plot)
* Top 10 profitable routes (bar plot)
* Scatter plot of occupancy vs revenue per seat

## Tools

* SQLite (Data Source)
* Python: pandas, matplotlib, seaborn
* Jupyter Notebook

---

Generated as part of the Airlines Data Science Project.
