# NOAA-Temperature-Analysis
## Overview
This project analyzes temperature trends in Ann Arbor, Michigan, and the United States using NOAA climate data from 2015. The goal is to examine daily high and low temperatures, visualize trends, and provide insights into seasonal variations.

## Key Steps in the Analysis
### Data Preprocessing:

Loaded temperature.csv and converted the date column to datetime format.
Filtered data to include only 2015 records.
Removed leap day (February 29th) for consistency.
Converted temperature values from tenths of degrees Celsius to Celsius.
### Ann Arbor Temperature Summary (2015):

Extracted data from stations near Ann Arbor, Michigan.
Visualized daily maximum (TMAX) and minimum (TMIN) temperatures over the year.
Identified temperature fluctuations and seasonal changes.
### United States Temperature Summary (2015):

Aggregated nationwide temperature data.
Computed daily average high and low temperatures across all stations.
Plotted national temperature trends over the year.
### Data Visualization:

Line plots for temperature trends using Matplotlib & Seaborn.
Geospatial mapping of weather stations using Folium.
Ensured clear legends, labels, and formatting for readability.
## Technologies Used
🟢 Data Processing: pandas, numpy
🟢 Visualization: matplotlib, seaborn
🟢 Mapping: folium
🟢 Notebook & Documentation: Jupyter Notebook, GitHub

## Findings & Insights
✅ Ann Arbor Trends:
Coldest months: January-February
Warmest months: July-August
Clear temperature cycles with occasional spikes.
✅ U.S. Trends:
Nationwide warming trend in summer.
Regional variations in daily temperatures.
## Next Steps & Improvements
- Compare 2015 vs. 2005-2014 to identify anomalies.
- Highlight record-breaking temperature days in 2015.
- Expand analysis with state-wise trends and additional climate factors.
