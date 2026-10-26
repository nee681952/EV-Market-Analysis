# 🚗 Electric Vehicle (EV) Market Analysis Dashboard

An end-to-end Business Intelligence project analyzing Electric Vehicle (EV) registration trends, manufacturer market share, regional adoption patterns, and YoY growth dynamics using **Power BI** and **DAX**.

---

## 📌 Project Overview
The transition toward electric mobility is rapidly accelerating. This project provides a multi-dimensional analysis of electric vehicle adoption across states, vehicle categories (2-Wheelers, 3-Wheelers, 4-Wheelers, Commercial Vehicles), manufacturers, and time periods. 

The dashboard enables stakeholders, automobile analysts, and policy researchers to track EV adoption trajectories, identify leading manufacturers, and uncover regional market penetration opportunities[cite: 5].

---

## 🛠️ Tech Stack & Tools
- **Business Intelligence Tool:** Microsoft Power BI Desktop[cite: 5]
- **Data Modeling & Analytics:** DAX (Data Analysis Expressions)[cite: 5]
- **Data Transformation & Cleaning:** Power Query Editor
- **Data Source:** Relational Electric Vehicle Dataset (`EV_Market_Analysis`)[cite: 5]

---

## 📊 Key Business Metrics & DAX Measures
Custom DAX measures were engineered to drive interactive analytics across report pages[cite: 5]:

- **Overall EV Registrations:** Total cumulative EV registrations across all recorded categories and years[cite: 5].
- **Selected Year Registrations:** Dynamic measure filtering registrations based on user-selected time slices[cite: 5].
- **Total Registrations:** Aggregated volume calculation handling multi-attribute filter contexts[cite: 5].
- **YoY Growth %:** Year-over-Year percentage change to quantify adoption momentum and expansion rates[cite: 5].

---

## 📑 Dashboard Architecture & Report Pages

### 1. Electric Vehicle Market Analysis (Executive View)[cite: 5]
* **KPI Metric Cards:** High-level summary of total EV registrations[cite: 5].
* **Adoption by Vehicle Type:** Clustered column chart categorizing registrations across vehicle segments[cite: 5].
* **State-Wise Distribution:** Clustered horizontal bar chart ranking top states by EV adoption[cite: 5].
* **Yearly Registration Trend:** Multi-year line chart displaying annual adoption curves[cite: 5].
* **Top Manufacturers:** Manufacturer ranking visual highlighting EV market share leaders[cite: 5].
* **Dynamic Slicers:** Interactive filtering by `Year` and `Vehicle Type`[cite: 5].

### 2. Detailed EV Analysis (Deep-Dive View)[cite: 5]
* **Growth KPIs:** Focused metric cards for `Selected Year Registrations` and `YoY Growth %`[cite: 5].
* **State vs. Year Matrix (Pivot Table):** Tabular breakdown of state-level adoption cross-tabulated across multiple years[cite: 5].
* **Segment Breakdown by State:** Stacked column visual showing vehicle type mix within each state[cite: 5].
* **Manufacturer Performance:** In-depth comparative volume analysis across leading EV brands[cite: 5].
* **Time-Series Analysis:** Longitudinal trend tracking multi-year adoption volume[cite: 5].

---

## 💡 Key Business Insights
1. **Adoption Momentum:** Significant positive trajectory in Year-over-Year (YoY) registration volumes reflecting growing market maturity.
2. **Segment Dominance:** High adoption concentrated in specific vehicle segments, highlighting key consumer adoption entry points.
3. **Geographic Concentration:** Regional hubs leading adoption, indicating a correlation with charging infrastructure maturity and local state incentives.
4. **Manufacturer Competition:** Market leadership is driven by top-tier manufacturers, with emerging entrants capturing specialized market segments.

---

## 🚀 How to Run the Project
1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/).
2. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/Electric-Vehicle-Market-Analysis.git
