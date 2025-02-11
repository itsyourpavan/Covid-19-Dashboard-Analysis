# COVID-19 Dashboard

## Problem Statement
The COVID-19 pandemic has had a significant impact globally, requiring real-time tracking and analysis to understand its spread, mortality rates, and recovery trends. This dashboard provides interactive visualizations to help analyze COVID-19 data, supporting better decision-making in public health and policy planning.

## Overview
This **COVID-19 Dashboard** built in Tableau offers a comprehensive analysis of key metrics related to the pandemic. It enables users to explore trends, compare different regions, and assess the impact of COVID-19 over time.

## Features
- **Total Cases, Deaths, and Recoveries**: Provides an overview of cumulative numbers.
- **Daily Case Trends**: Line chart showcasing new cases, deaths, and recoveries per day.
- **Geographical Spread**: Interactive map showing COVID-19 cases by region/country.
- **Mortality & Recovery Rates**: Pie charts displaying fatality and recovery percentages.
- **Comparative Analysis**: Allows filtering by country/region for in-depth comparisons.
- **Vaccination Progress**: If data is available, includes vaccination trends and distribution.
- **Indian State-Level Visualization**: Includes Indian state shapefile for more detailed state-level analysis.

## Dashboard Visuals & Titles
1. **Global COVID-19 Overview** - Key metrics on total cases, recoveries, and deaths.
2. **Daily Trends Analysis** - Line charts tracking the daily progression of cases.
3. **Geographical Spread of COVID-19** - Interactive map displaying case distribution.
4. **Mortality vs. Recovery Rates** - Pie charts breaking down recovery and death rates.
5. **Country-wise Comparison** - Bar charts comparing COVID-19 metrics across different countries.
6. **Vaccination Insights** (if applicable) - Trends in vaccination rollout.
7. **Indian State-Level Analysis** - State-wise COVID-19 cases using Indian state shapefile.

## Process Overview
### 1. Data Collection & Loading
- Collected data from Kaggle, sourced from publicly available COVID-19 datasets.
- Loaded data into **Tableau** for interactive visualization.
- Integrated **Indian state shapefile** for state-level visualization.

### 2. Data Cleaning & Preparation
- Removed duplicate or inconsistent entries.
- Standardized country and region names.
- Filled missing values using appropriate estimation methods.
- Created calculated fields for **fatality rate, recovery rate, and active cases**.

### 3. Data Transformation & Feature Engineering
- Derived new metrics such as **case growth rate, moving averages, and trend lines**.
- Applied **date filters** to allow dynamic period selection.
- Designed **region-wise drill-down capabilities** for a granular view.
- Implemented **Indian state-wise breakdown** for more localized insights.

### 4. Creating Visuals
- Developed **interactive Tableau dashboards** with relevant KPIs.
- Used **bar charts, line graphs, maps, and pie charts** for better insights.
- Implemented **filters and parameters** to enhance user experience.
- Created **Tableau calculated fields** to compute essential COVID-19 statistics.
- Added **Indian state-wise map** using a shapefile for better geographical insights.

## Technologies Used
- **Tableau**: For interactive data visualization.
- **Python (Pandas, NumPy)**: Data preprocessing (if applicable before loading into Tableau).
- **SQL**: Querying and filtering large datasets for efficient visualization.
- **Indian State Shapefile**: For detailed Indian state-level COVID-19 analysis.
- **Kaggle**: Primary data source for COVID-19 case data.

## How to Use
1. Open the **Tableau** `.twb` file.
2. Use filters to explore trends in specific regions.
3. Interact with maps and charts to analyze COVID-19 patterns.
4. Compare different countries' performance in managing the pandemic.
5. View **Indian state-wise data** through the shapefile visualization.

## Key Insights
- COVID-19 cases show **seasonal trends** with multiple waves in different regions.
- Certain countries have **higher fatality rates** due to healthcare system strain.
- **Vaccination rollout correlates with a decline in new cases** in some regions.
- High urban density areas experience **faster virus transmission**.
- Indian states exhibit **varying COVID-19 impacts**, requiring localized interventions.

## Future Improvements
- Add **real-time API integration** for live COVID-19 updates.
- Incorporate **predictive modeling** to forecast future case trends.
- Expand **vaccination dataset** for deeper analysis.
- Improve **Indian state-level mapping** with enhanced region-specific insights.

## Contributing
If you'd like to improve this dashboard or enhance its functionality, feel free to **fork this repository** and submit a pull request with your contributions.

## Author
Developed by itsyourpavan. Connect with me for further discussions on **data analytics and visualization!**

