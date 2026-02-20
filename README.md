# bike-buyers-sales-analysis-excel
Excel analysis of bike buyer behaviour — from raw data to an interactive sales dashboard.

Bike Sales Analysis — Excel Data Analytics Project

Who buys bikes and why? This project digs into real customer data to uncover how income, age, gender, and commute distance influence purchasing decisions — built  in Microsoft Excel.


# Project Overview
This is a data analytics project completed in Excel, covering every stage of the data workflow — from messy raw data through to a polished, interactive dashboard. The goal was to identify the key demographic and behavioural factors that separate bike buyers from non-buyers, and present those findings in a clear, decision-ready format.

# Workbook Structure
Bike_buyers - Original raw dataset
Working Sheet -  Cleaned and transformed data ready for analysis
PivotTable - Aggregated summaries powering the dashboard
Dashboard - Interactive visualisation with slicers and filters

# What Was Done:
Data Cleaning & Preparation
Removed duplicate records to ensure data integrity
Standardised categorical fields (e.g. gender, marital status, region)
Formatted income columns and corrected inconsistencies across the dataset
Applied nested IF formulas to engineer a new Age Brackets column, categorising customers into Adolescent, Middle Aged, and Old segments

=IF(L2>54,"Old",IF(L2>=31,"Middle Aged",IF(L2<31,"Adolescent","Invalid")))

# Pivot Table Analysis
Built multiple pivot tables to slice the data across key dimensions:

Average Income by gender and purchase decision
Purchase Count by commute distance
Customer distribution by age bracket and purchase behaviour

# Interactive Dashboard
Designed a clean, filterable dashboard featuring:

Bar chart — Average income per purchase, broken down by gender
Line chart — Bike purchases across age brackets (Adolescent → Middle Aged → Old)
Line chart — Customer commute distance vs. purchase rate
Slicers for dynamic filtering by Gender, Age Bracket, and Commute Distance


# Key Insights

Income drives purchases — Customers who bought a bike earned higher average incomes across both genders. Male buyers averaged £60,124 vs £56,208 for non-buyers.
Middle Aged customers are the core market — This age group showed the highest volume of bike purchases, significantly outpacing both Adolescent and Old segments.
Shorter commutes = more buyers — The 0-1 mile commute bracket had the highest purchase count (200 buyers), with rates dropping steadily as commute distance increased.
Gender gap exists but is consistent — Males purchased at a higher rate than females, though both genders followed the same income and commute trends.


# Skills Demonstrated
Data Cleaning · Data Validation · Deduplication · Feature Engineering · Pivot Tables · Data Visualisation · Dashboard Design · Slicers & Filters · Nested IF Logic · Analytical Thinking


![Bike Sales Dashboard](./Excel%20final%20dashboard.png)
Interactive slicers allow filtering by gender, age bracket, and commute distance in real time.

Three interconnected charts provide a complete view of purchasing behavior from income, demographics, and commute patterns
- Dynamic filtering via slicers allows users to drill down into specific customer segments instantly — select "Middle Aged" and "Europe" to see how that cohort behaves
- Consistent color coding (orange for buyers, blue for non-buyers) makes it easy to spot patterns at a glance
- Professional layout with clear section headers and strategic spacing guides users through the analysis
- All visualizations update simultaneously when filters are applied, enabling quick "what-if" exploration


