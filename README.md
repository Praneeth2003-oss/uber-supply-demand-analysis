# uber-supply-demand-analysis

A data-driven case study exploring Uber’s operational challenges in managing supply and demand for airport pickups and drop-offs.

---

## Problem Statement
Uber is facing frequent driver cancellations and unavailability of cabs for trips to and from the airport. This mismatch results in poor user experience and significant revenue loss.

--

## Objective
To identify the root causes of the supply-demand gap in Uber rides specifically between the City and Airport, and recommend data-driven operational solutions.

---

## Dataset 📁
- [Uber Data.csv](https://github.com/Praneeth2003-oss/uber-supply-demand-analysis/blob/6ecd785a7d7577e59aa273f6da01c8b90e6bb986/Uber%20Data.csv)
- [Uber_Data.csv](https://github.com/Praneeth2003-oss/uber-supply-demand-analysis/blob/80d15efa8bf28cd6817d806b064e1143fba7c466/Uber_Data.csv)

---

## Tools Used 
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook for exploratory data analysis
- Microsoft Excel

---

### Data Preparation
- Imported and merged raw data
- Cleaned data and fixed formatting issues
- Standardized time & date columns
- Created new variables for time-slot analysis

### Exploratory Data Analysis
- Segmented data by pickup points and time of day
- Analyzed types of requests: `Completed`, `Cancelled`, `No Cars Available`
- Focused on airport-related trends across time windows

---

## Key Insights

- 16% cancellations primarily occur in the City during morning hours (5 AM – 9 AM)
- 25% no availability primarily occurs at the Airport in evening hours (5 PM – 10 PM)
- A total 58% gap in cab supply was observed across the 5-day data
- 15% due to cancellations (morning, city)
- 15% due to no cars available (evening, airport)

---

## Business Impact

Without intervention, Uber risks:
- Losing **~58% of potential revenue** during peak demand
- Poor user satisfaction due to frequent cancellations and no-shows
- Reduced driver utilization and inefficient dispatching

---

## ✅ Recommendations

- Incentivize airport trips during peak demand hours.
- Assign dedicated airport-bound cabs during morning/evening rush.
- Set a base compensation for drivers returning empty from the airport.
- Impose penalties for frequent cancellations by drivers.
- Promote advance bookings for airport rides.
- Share live flight schedules with drivers to sync demand forecasting.
