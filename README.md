# Economic Sector Analysis Dashboard

## Introduction

This project focuses on analyzing economic sector data using Power BI. The dataset includes indicators such as current prices, constant prices, sector classification, and time-based trends (annual and quarterly).

The goal of this project is to understand:

- Sector-wise economic contribution
- Growth trends over time
- Differences between current and constant prices
- Impact of inflation on economic indicators

The dataset required extensive data cleaning and preprocessing, including handling missing values, managing mixed units (₹ Crore and %), and creating new features such as Sector Name, Year_Start, and Period.

## Data Preparation

Key steps performed:

- Removed duplicate records
- Handled missing values:
- Used Unknown where both fields were empty
- Used N/A where not applicable
- Filtered inconsistent units (₹ Crore vs %)
- Created new columns:
   Sector Name (merged categorical fields)
   Year_Start (for proper sorting)
   Period (Annual / Quarterly)
- Cleaned and formatted data for Power BI analysis

## Dashboard Features

Page 1: Overview Dashboard
KPI Cards:
- Total Current Price
- Total Constant Price
- Price Difference
- Top 8 Sector Contribution (Bar Chart)
- Year-wise Trend (Line Chart)
Interactive slicers:
- Year
- Frequency
- Quarter
Page 2: Detailed Analysis
- Growth % Trend (Line Chart)
- Current vs Constant Price Comparison (Clustered Column Chart)
- Subindustry Distribution (Donut Chart)
- Institutional Sector Contribution(Clustered Bar Chart)

##  Dashboard Preview

### Page 1: Overview Dashboard
![Overview Dashboard](Dashboard_Page1.png)

### Page 2: Detailed Economic Analysis
![Detailed Dashboard](Dashboard_page2.png)

## Key Insights

- The service-related sectors contribute the highest share to total economic output
- There is a consistent increase in current prices over time, indicating economic growth
- The gap between current and constant prices highlights the impact of inflation
- Growth trends show fluctuations in recent years, possibly due to incomplete or recent data
- A small portion of data categorized as "Unknown" was excluded to improve analysis quality

## Tools Used

- Power BI – Dashboard creation and visualization
- Python (Pandas, Matplotlib, Seaborn) – Data cleaning and EDA
- Excel – Initial data handling

## Conclusion

This project demonstrates how raw economic data can be transformed into meaningful insights through proper data cleaning and visualization techniques.
By comparing current and constant prices, the analysis provides a clear understanding of:

- Sector-wise economic performance
- Inflation effects
- Growth patterns over time

The dashboard enables users to interactively explore the data and gain valuable insights for decision-making and analysis.
