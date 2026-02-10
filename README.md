✈️ Airline Delay Analytics — Frontier Airlines @ Chicago O’Hare (ORD)

This project analyzes operational performance and delay behavior for Frontier Airlines (F9) at Chicago O’Hare International Airport (ORD) using a clean, KPI-safe data model built in KNIME + Power BI.

The goal is to understand how reliably flights depart from ORD and identify whether delays are driven by congestion, scheduling, or operational disruptions.

This repository contains the Phase-1 analysis, focused on a single airline (Frontier) at a single airport (ORD) to ensure analytical rigor before expanding to cross-airline comparisons.


🔧 Tools Used

KNIME → data cleaning, joins, feature engineering, KPI logic

Power BI → data modeling, measures, dashboard design

GitHub → project versioning and portfolio presentation

📊 Key Metrics Analyzed

Late Departure Rate (15+ min)

Flight Cancellation Rate

Flight Diversion Rate

Average Taxi-Out Time

Delay trends over time

Congestion vs delay correlation

All KPIs are calculated using flag-based logic to avoid bias from cancelled or diverted flights.


🎯 Project Focus (Phase-1)

This version of the dashboard is intentionally scoped to:

Airline: Frontier Airlines (F9)
Airport: Chicago O’Hare (ORD)

This allows for:

Correct KPI construction

Clean operational analysis

Reliable time-series trends

Defensible methodology


🔍 Key Insight

Taxi-out congestion at ORD strongly correlates with late departures, suggesting that ground movement and runway pressure are major contributors to operational delays for Frontier flights.


🚧 Upcoming Expansion (Phase-2)

This project will be extended to analyze additional high-traffic airlines operating at ORD, including:

United Airlines

American Airlines

Southwest

Delta

The goal of Phase-2 is to build a multi-airline comparative dashboard to evaluate:

Reliability differences by carrier

Airport congestion impact

Operational efficiency benchmarking

This will evolve into a full airport-centric operations analytics project.


📁 Repository Contents
/PowerBI
  Frontier_ORD_Dashboard.pbix

/screenshots
  dashboard.png

/Data


💡 Why This Project Matters

This project demonstrates:

Proper KPI modeling for aviation analytics

Clean star-schema design

Bias-safe delay calculations

Operational insight generation

Dashboard design for decision-making

It is built to reflect real-world airline operations analysis, not just visualization.


📬 Future Work

Multi-airline ORD comparison

Arrival performance analysis

Root-cause delay attribution

Airport congestion modeling

Predictive delay modeling


Author

Umang Gupta


⭐ If you’re viewing this repo

Feel free to explore the dashboard and methodology.
More airline analyses for ORD will be added soon.
