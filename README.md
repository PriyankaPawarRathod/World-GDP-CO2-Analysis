# World-GDP-CO2-Analysis
This project analyzes and visualizes the relationship between GDP per capita and CO₂ emissions using World Bank data (1960-2015). Includes bar charts, line plots, histograms, and scatter plots.
# Visualization of World GDP and Carbon Dioxide Emission

## About This Project
This project explores how **GDP per capita** and **CO₂ emissions per capita** are related over time. The dataset spans **1960 to 2015**, covering **247 countries** and **over 5.6 million records**. Various visualizations help analyze trends and patterns in economic growth and carbon emissions.

## Dataset Details
- **Data Source:** Extracted from World Bank Indicators
- **File Used:** `Indicators.bz2`
- **Columns Included:**
  - `CountryName`: Represents the country name
  - `CountryCode`: Standardized country code
  - `IndicatorName`: Specifies the measured indicator (e.g., CO₂ emissions, GDP per capita)
  - `IndicatorCode`: Unique code for the indicator
  - `Year`: Represents the recorded year
  - `Value`: The actual measured value

## Visual Representations
- **Bar Chart:** CO₂ emissions trend for the USA over different years
- **Line Plot:** Yearly fluctuations in CO₂ emissions for the USA
- **Histogram:** Distribution of CO₂ emissions across different time periods
- **Scatter Plot:** Examining the connection between GDP per capita and CO₂ emissions per capita

## Key Insights
- The USA experienced a steady GDP increase between **1960 and 2014**.
- CO₂ emissions data is recorded until **2011**, revealing varying regional trends.
- Developed nations exhibited **higher CO₂ emissions**, while developing countries had comparatively lower levels.
- The correlation between GDP and CO₂ emissions is weak (`0.07`), highlighting the role of additional factors such as **energy consumption, technological advancements, and policy regulations**.

## How to Execute This Project
1. Install necessary dependencies:
   ```bash
   pip install pandas numpy matplotlib
   ```
2. Run the Jupyter Notebook or Python script to generate the visualizations.

## Future Scope & Enhancements
- Conduct a deeper analysis of country-wise trends.
- Incorporate additional environmental indicators to provide a more comprehensive perspective.
- Investigate the impact of renewable energy and policy decisions on CO₂ reduction.

---
  
   "Created by Priyanka Pawar" 

