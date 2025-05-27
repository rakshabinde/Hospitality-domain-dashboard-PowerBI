 📊 Revenue Insights Dashboard – Hospitality Domain | Power BI

A comprehensive **Power BI dashboard** project designed to deliver **revenue insights** and **operational performance analytics** for the **hospitality sector**. The dashboard empowers hotel businesses to make real-time, data-driven decisions through interactive and insightful visuals.



🚀 Project Objective

To build a fully interactive and dynamic dashboard that enables hospitality stakeholders to analyze:

* Total revenue by city and room class
* Key performance indicators (KPIs) like RevPAR, Occupancy %, ADR, and Realization %
* Weekly and category-based revenue trends
* Booking platform performance (e.g., MakeYourTrip, Tripster, Direct Online, etc.)



🧰 Tools & Technologies Used

🔹 Power BI Desktop

* **Main visualization tool** used to connect, clean, model, and visualize the hospitality dataset.
* Built various charts (bar, line, donut, matrix, slicers) to allow dynamic analysis of KPIs.

🔹 Power Query Editor

* Used to clean, transform, and shape raw data (ETL process).
* Applied data type changes, removed unnecessary columns, and standardized city and platform names.

 🔹 DAX (Data Analysis Expressions)

* Created custom measures and calculated columns:

  * `RevPAR = Revenue / Available Room Nights`
  * `Occupancy % = (Booked Room Nights / Sellable Room Nights) * 100`
  * `Realization % = (Revenue / (Booked Room Nights * ADR)) * 100`
* Used time intelligence functions to compute week-on-week changes and performance splits (Weekday vs. Weekend).

🔹 Data Modeling

* Established relationships between dimension tables (e.g., Cities, Platforms) and fact tables (e.g., Booking, Revenue).
* Ensured **star schema** layout for efficient querying and filtering.

🔹 Slicers & Filters

* Interactive filters were added for:

  * City
  * Room class
  * Booking platform
  * Time period (weeks/months)



📌 Key Features

* 🗺️ City-Wise Revenue Analysis: Compare revenue, occupancy, and RevPAR across multiple cities like Mumbai, Bangalore, Delhi, and Hyderabad.
* 🏷️ Booking Platform Realization: Evaluate ADR and Realization % per booking platform to inform marketing and distribution strategies.
* 📅 Time Series Trends: Analyze performance over weeks (W19–W32), revealing seasonality or operational shifts.
* 💡 Category Performance: Breakdown between **Luxury** and **Business** room classes to identify segment-specific opportunities.
* 📉 KPI Benchmarking: Instantly monitor how the hotel portfolio is performing using visual KPI cards.



 🧠 What I Learned

* Advanced DAX formula writing for real-time KPI calculations
* Data modeling best practices in BI environments
* Optimizing dashboard performance through query reduction
* Building executive-level dashboards tailored to business needs





