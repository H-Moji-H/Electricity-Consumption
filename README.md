# Electricity Consumption Analysis: Project Summary
Overview
This project analyzes household electricity consumption and solar electricity generation to evaluate the cost-effectiveness of installing a battery system. Naomi, the homeowner, generates solar electricity and currently uses it directly to meet her energy needs. Excess electricity is wasted, prompting the consideration of a battery system to store surplus power for later use. The analysis leverages real-world data from 2020 to explore potential savings from the battery installation.

Objective
To determine whether purchasing a battery would reduce Naomi's electricity costs by storing surplus solar energy and reducing reliance on electricity purchased from the grid.

Data and Methodology
Dataset: Hourly electricity usage and solar electricity generation data for 2020 (excluding February 29).
Key Metrics:
Solar electricity generation (kWh).
Household electricity usage (kWh).
Electricity price trends with inflation.
Assumptions:
Electricity prices start at $0.17/kWh in 2022, with annual inflation rates starting at 4%, increasing by 0.25% each year.
Battery cost: $7,000, with a lifetime of 20 years.
Maximum battery storage capacity: 12.5 kWh.
Analysis Steps
Data Cleaning:
Handled missing data and formatted columns for consistency.
Exploratory Data Analysis (EDA):
Identified patterns in electricity consumption and solar generation.
Visualized daily and seasonal usage trends.
Battery Simulation:
Simulated energy flow using battery storage:
Prioritized solar electricity for immediate usage.
Stored excess solar energy in the battery.
Used battery power when solar generation was insufficient.
Purchased grid electricity as a last resort.
Cost Savings:
Compared electricity costs with and without the battery over 20 years.
Incorporated inflation to project future costs.
Key Insights
Solar Efficiency:
Significant mismatch between solar generation and consumption during peak hours leads to wastage.
Battery Impact:
Storing excess solar energy drastically reduces reliance on grid electricity.
Projected Savings:
Over 20 years, the battery investment offsets initial costs, leading to significant long-term savings.
Electricity Price Trends:
Rising electricity prices amplify the benefits of solar energy storage.
Conclusion
Installing a battery system is a cost-effective solution for Naomi. By harnessing excess solar energy, Naomi can significantly reduce her dependency on grid electricity, mitigate the impact of rising electricity prices, and save money in the long term.

Repository Contents
Notebook: Full analysis and visualization code in Python.
Dataset: Hourly electricity usage and solar generation data for 2020.
Report: Comprehensive insights and results of the analysis.
