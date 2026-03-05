# Enterprise Supply Chain Optimization & Spend Analytics

## **Project Overview**

**The Chaos on the Ground:** Operations leaders were flying blind. Critical spending and logistics data were fragmented across multiple disconnected systems, making it impossible to map physical unit movement against discretionary spend.
**The Solution:** I built an interactive Supply Chain Command Center—a unified front-end analytical layer that standardized 15.4 million records of fragmented competitor data and resolved over 10,000 location errors. This established a reliable "Golden Record," eliminating physical logistics bottlenecks and actively monitoring the disconnect between compliance risk, sales cyclicality, and actual logistics throughput.

## **Data Sources**

- **Enterprise Data Warehouse Extract (CMS Open Payments):** Aggregated and highly structured CSV outputs generated from a custom MySQL Star Schema (15M+ rows).
- **Geospatial Reference Maps:** Lat/Lng grain crosswalks to measure accurate physical transit realities.

## **Process**

- **SQL Engineering:** Replaced manual guesswork and spreadsheet crunching with Z-Score statistical thresholds hardcoded into SQL to mathematically isolate anomalous spending behavior.
- **Demand Forecasting Logic:** Developed leading/lagging indicator models to trigger `HOT MARKET`, `AT RISK`, or `STOCKPILING` signals based on real-time data flows.
- **Interactive Control Tower:** Engineered 3 Tableau Dashboards utilizing Dual-Axis synchronizations and Lorenz Curves to filter complex relational data across Geographies and Specialties instantly.

## **Key Findings**

- **Compliance Exposure:** Uncovered **$11.7M in organizational spend risk** (a critical DOJ audit trigger) by mathematically isolating discretionary spend, mapping physical supply chain friction to guide executive-level demand planning.
- **Logistics Optimization:** Proved that **San Diego** drives significantly higher surgical device throughput than Los Angeles, challenging legacy population-based assumptions.
- **Customer Concentration:** The Whale Curve revealed that over **80% of commercial revenue** relies on just the **Top 2%** of active accounts.

## **Recommendations (Operational Scripts)**

- **CCO (Compliance) Roadmap:** Execute immediate internal audits on the specific ZIP codes flagged in the Risk Matrix, isolating the "Unknown Product" payments.
- **COO (Logistics) Roadmap:** Shift the next West Coast Forward Stocking Location (FSL) prioritization to San Diego to minimize true "last mile" transit times for high-volume units.
- **CRO (Growth) Roadmap:** Deploy targeted retention protocols for the "Top 2% Platinum" accounts to stabilize extreme quarterly revenue cyclicality.

## **Next Steps**

- **Proactive Maintenance:** Evolve the Demand Forecasting matrix from a visual heatmap into a Machine Learning model that automatically triggers inventory purchase orders before stockouts occur.
- **Golden Record Iteration:** Set up automated alert subscriptions so operations teams are instantly notified the moment a designated target's Z-Score crosses the danger threshold.
