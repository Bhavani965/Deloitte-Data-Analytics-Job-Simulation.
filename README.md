# Deloitte-Data-Analytics-Job-Simulation.
Data analysis tasks completed for the Deloitte STEM Virtual Experience Program.

## Project Overview
This repository contains the tasks completed during the Deloitte Data Analytics virtual experience on Forage. The project involved analyzing telemetry data for a manufacturing client (Daikibo) and assessing unfair pay practices using forensic data analytics.

## Tools Used
- **Tableau:** For data visualization and dashboard creation.
- **Microsoft Excel:** For data manipulation and conditional logic.
- **JSON:** Handling large datasets.

---

## Task 1: Daikibo Telemetry Analysis (Tableau)
**Goal:** Analyze manufacturing telemetry data to identify the main causes of operational downtime.

**Process:**
- Imported JSON telemetry data into Tableau.
- Created a calculated field (`Unhealthy`) to quantify downtime duration.
- Visualized downtime by **Factory Location** and **Machine Type**.
- Built an interactive dashboard allowing users to filter machine data by selecting a factory.

### Dashboard Preview
![Tableau Dashboard Screenshot](tableau_dashboard.png)

[**🔗 Click Here to View the Interactive Dashboard on Tableau Public**](PASTE_YOUR_TABLEAU_PUBLIC_LINK_HERE)

---

## Task 2: Forensic Technology Equality Analysis (Excel)
**Goal:** Investigate employee compensation data to identify potential unfair pay based on an equality score.

**Process:**
- Analyzed a dataset of employee roles and equality scores.
- Created a complex nested `IF` function in Excel to classify scores:
    - **Highly Discriminative:** Score > 20 or < -20
    - **Unfair:** Score > 10 or < -10
    - **Fair:** Score between -10 and 10

### Excel Logic
![Excel Screenshot](excel_logic.png)
