### **Business Problem:**

Our airline company operates a diverse fleet, ranging from small jets to medium-range aircraft, with a long-standing reputation for delivering premium air transportation services. Despite our dedication to safety, comfort, and efficiency, the company’s **profitability is under mounting pressure** due to **external economic and regulatory constraints**.

To remain competitive and financially viable, the management is turning to **data-driven analysis** using the internal travel database (`travel.sqlite`) to uncover actionable insights. The key business question is:

> **"How can we increase the occupancy rate and overall profitability across flights by optimizing routes, pricing, aircraft utilization, and customer experience?"**

---

### **Main Challenges:**

1. **Environmental Regulation Compliance**
   Growing pressure to reduce the aviation carbon footprint has led to **new regulations and emissions-based penalties**, raising operational costs and limiting expansion potential.

2. **Escalating Flight Taxes**
   Governments are levying higher taxes on airline operations to address climate goals, making flights more expensive for passengers and reducing **price elasticity and demand**.

3. **Labor Market Constraints**
   The **shortage of skilled aviation workers** is leading to increased labor costs, turnover, and operational inefficiencies—affecting crew scheduling, aircraft turnaround time, and flight delays.

4. **Low Occupancy on Specific Routes**
   Some routes consistently show **underperformance** in terms of occupancy and profitability, potentially due to poor scheduling, mismatch between demand & supply, or poor customer experience.

---

### **Analytical Objectives:**

1. **Maximize Occupancy Rate**
   Analyze route, aircraft type, seasonal patterns, and ticketing trends to **identify underperforming flights** and recommend actions to increase passenger load factor.

2. **Optimize Pricing Strategy**
   Use historical ticket price vs. occupancy data to design a **dynamic pricing model** that adapts to demand, route popularity, seasonality, and customer profiles.

3. **Enhance Customer Journey**
   Identify pain points in the **booking, seating, and boarding process** using `tickets`, `seats`, and `boarding_passes` data, and propose improvements to drive loyalty and satisfaction.

4. **Improve Aircraft & Route Utilization**
   Combine `flights`, `aircrafts_data`, and `ticket_flights` to evaluate **profit per flight** and suggest better fleet deployment based on demand patterns.

---

### Final Goal:

> To **pinpoint actionable opportunities**—whether in pricing, scheduling, fleet assignment, or customer experience—that can lead to **higher seat occupancy on low-performing flights** and overall **profit optimization**, all backed by insights from the `travel.sqlite` dataset.

---

### Dataset Tables Summary for Mapping:

| Table             | Potential Use                               |
| ----------------- | ------------------------------------------- |
| `flights`         | Schedule, delays, aircraft mapping          |
| `bookings`        | Total revenue, passenger counts             |
| `tickets`         | Customer segmentation, pricing patterns     |
| `ticket_flights`  | Flight-wise ticket revenue                  |
| `seats`           | Aircraft seating capacity and configuration |
| `aircrafts_data`  | Aircraft type, range, and economics         |
| `airports_data`   | Route feasibility, demand zones             |
| `boarding_passes` | Boarding trends, late/no-show passengers    |

---
