Patient & Financial Analysis Dashboard

📊 Project Overview

This Power BI project provides a comprehensive analysis of healthcare data, merging patient demographics with financial performance metrics. The dashboard is designed to help hospital administrators and financial officers monitor revenue trends, payer performance, and encounter-based claims.

The dashboard tracks 974 total patients with a total revenue of $101.51M, offering a granular look into how different patient segments and insurance providers contribute to the bottom line.

🚀 Key Features

Executive Summary Tiles: At-a-glance view of Total Patients, Revenue ($101.51M), Average Visit Cost ($3.64K), and Coverage Ratio (30.63%).

Revenue Trend Analysis: A historical timeline (2012–2022) showing revenue fluctuations, peaking at $12M in 2014.

Payer Performance: Horizontal bar charts identifying the top 5 payers, including Medicare, Medicaid, and private insurers like Blue Cross Blue Shield.

Encounter Classification: A donut chart breaking down claims by encounter class (Ambulatory, Urgent Care, Outpatient, Emergency, Inpatient, and Wellness).

Dynamic Tooltips: Custom hover-over tooltips that display "Cost Claim by Gender" and specific "Top 5 Payer" breakdowns for deeper data exploration without cluttering the main view.

Interactive Slicers: Capability to filter the entire dataset by City (e.g., Baltimore, Chicago, Hartford) and Gender.


🛠️ Data Insights 

Insurance Gap: A significant portion of the claim cost is categorized under "NO_INSURANCE," highlighting a potential area for financial risk management.

Gender Distribution: Tooltips reveal that in specific sectors (like Baltimore), Male patients contribute significantly higher revenue ($16.3M) compared to Female patients ($8.3M).

High-Value Encounters: Ambulatory visits represent the largest share of claims at approximately 35.74% ($36.28M).

📸 Screenshots
Main Dashboard

A high-level view of all financial and patient KPIs.

Drill-down Tooltips
Demonstrating the interactive "Cost Claim by Gender" tooltip.

🔧 Technical Stack
Tool: Power BI Desktop

Data Source: encounters.csv,organizations.csv,patients.csv,payers.csv,procedures.csv.

DAX Measures: Used for calculating Revenue, Coverage Ratios, and Average Costs.

Visuals: Clustered Bar Charts, Line Charts, Donut Charts, and Card Visuals.

📂 How to Use

Download the .pbix file from the repository.

Ensure you have Power BI Desktop installed.

Open the file to interact with the filters (City, Gender) and hover over data points to see the custom tooltips in action.
