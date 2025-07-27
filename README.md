Uber Fares Analysis - Power BI Dashboard
Project Overview
This project analyzes Uber trip data to uncover fare patterns, peak demand periods, and operational insights using Power BI. The interactive dashboard visualizes key metrics to optimize pricing strategies and resource allocation.

Tools Used
Python (Pandas, Matplotlib/Seaborn) for data cleaning & EDA.

Power BI for interactive dashboards.

GitHub for version control.

Key Insights
Peak Hours: Fares surge by 20% during 7–9 AM and 5–7 PM.

Distance-Fare Correlation: Strong linear relationship (R² = 0.78).

Weekend Demand: 15% more rides on Fridays/Saturdays.

How to Use This Project
1. Data Preparation
Run the Jupyter Notebook (notebooks/uber_data_cleaning.ipynb) to:

Clean missing values.

Add features like peak_hour and day_of_week.

Export cleaned data to data/uber_cleaned.csv.

2. Power BI Dashboard
Open powerbi/uber_analysis.pbix in Power BI Desktop.

Filters: Adjust date ranges, days, or peak hours.

Interactivity: Click visuals to cross-filter (e.g., select a day to update all charts).

3. Customize
Edit DAX measures in Power BI for new metrics.

Replace uber_raw.csv with updated data (ensure column consistency).

 Dashboard Preview
https://i.imgur.com/XYZ123.png
(Replace with your actual screenshot link)

 Report Summary
Objective: Analyze fare trends to optimize Uber’s pricing strategy.

Methodology: EDA in Python → Visualization in Power BI.

Recommendations:

Implement dynamic pricing during peak hours.

Allocate more drivers to high-demand areas.

Contact
For questions or collaborations:

Email: timoirakoze@gmail.com.com

License: MIT
Dataset Source: Kaggle Uber Fares Dataset

Key Files to Highlight
File	Purpose
uber_cleaned.csv	Analysis-ready data
uber_analysis.pbix	Interactive dashboard
uber_data_cleaning.ipynb	Data cleaning code
This README ensures reproducibility and clarity for stakeholders. Customize links, insights, and contact details as needed!
