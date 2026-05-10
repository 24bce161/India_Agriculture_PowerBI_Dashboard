**Rainfall Impact on Agricultural Productivity (1966-2017)**
Project Overview
This project provides a comprehensive data analysis of how monsoon rainfall patterns influence agricultural productivity across various Indian states. Using a historical dataset spanning over 50 years, the project identifies correlations between rainfall volumes and crop yields to help stakeholders make data-driven agricultural decisions.

Key Features & Tasks
Data Modeling: Implemented a Star Schema with a Central Fact Table and dimension tables for States and Years.

Dynamic Analysis: Utilized Power Query to unpivot complex crop data, enabling a single dashboard to analyze multiple crops (Rice, Wheat, Maize, Sorghum, etc.) dynamically.

Advanced DAX: Created measures for Average Rainfall, Total Production, and Average Yield to provide real-time insights based on user filters.

Interactive Visualizations: Built a multi-page dashboard featuring correlation scatter plots, temporal trend lines, and geographic maps.

Dashboard Insights
Correlation Analysis: A scatter plot with trend lines demonstrates the sensitivity of specific crops to rainfall fluctuations.

Temporal Trends: Line charts compare decadal rainfall changes against crop productivity, highlighting years of drought and surplus.

Regional Productivity: A geographic heatmap identifies the states with the highest yield efficiency relative to their average rainfall.

Rainfall Categorization: A bar chart analysis shows how productivity differs across 'Low', 'Medium', and 'High' rainfall categories.

Recommendations Derived
Risk Mitigation: Identified high-sensitivity regions that require priority investment in irrigation infrastructure to reduce reliance on monsoons.

Crop Diversification: Suggested shifting to hardy crops (like Millets or Pulses) in regions consistently falling into 'Low' rainfall categories.

Infrastructure: Recommended the development of water harvesting systems in states where high rainfall does not lead to proportional yield increases (indicating runoff/flood issues).

Tech Stack
Tool: Power BI Desktop

Language: DAX (Data Analysis Expressions)

Data Source: rain-agriculture.csv (Historical Indian Agricultural Data)
