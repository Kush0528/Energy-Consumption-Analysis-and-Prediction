# Energy-Consumption-Analysis-and-Prediction
## Project Overview
The purpose of this Analysis is to preemptively manage the expected increase in electricity demand during the summer months for the energy company (eSC) operating in South Carolina and parts of North Carolina and relieve the strain on the electrical grid during these high-demand periods without having to build new energy-generating facilities.The emphasis is on identifying the fundamental determinants that influence energy use, developing predictive models to forecast peak energy demand, and devising strategies to encourage energy saving among residential consumers.

## Project Outcomes
- Data Collection and Preparation
- Analysis of Energy Consumption 
- Predictive Modeling for Demand Forecasting 
- Interactive Data Visualization with Shiny Apps 

## Datasets Used:
- Static House Data
- Energy Usage Data
- Weather Data

## Data Processing Steps:
- House Classification - Classified houses based on their built area '<900' and climate zone = 'Hot-Humid'.
- Date Formatting - Standardized the format of the date column into a datetime format.
- Data Consolidation - Merged the Sample House Data (SHD) with the Energy Data (ED) using the building data as a linkage key.
- County-Wide Data Aggregation - Compiled and aggregated total humidity and temperature data at the county level.
- Comprehensive Data Integration - Merged county-level environmental data with detailed house-level data.
- County Grouping and Data Summarization - Organized and summarized weather data across entire counties, focusing on total humidity and temperature.

## Predictive Models Used:
- Linear Regression Model
- XGBoost Model

## Conclusion
The project successfully highlighted the critical factors affecting residential energy consumption and developed predictive models to forecast energy usage. The findings underscore the importance of targeted interventions such as upgrading insulation and lighting to reduce energy consumption. These insights and recommendations can help utility providers and policymakers implement more effective energy management strategies, promoting sustainability and reducing the strain on energy infrastructures during peak periods.