# Global-CO2-Emissions-Dashboard

**About this project**

The goal of this project was to explore and visualize global CO2 data in order to identify trends and patterns, with a focus on the largest contributors of CO2 emissions. The business needs revolved around gaining insights into CO2 emissions at the country level and understanding the relationships between CO2 emissions, population, and temperature change.

To achieve this, I started by connecting to the visualizing_global_co2_data CSV and profiling the data. I filtered out records that weren't at the country level and excluded NULL Iso Codes to optimize the data source for visualization. Additionally, I converted all fields with "Co2" in their name to be Number (Whole) data type and created a new integer type parameter named Top N to determine the top countries for analysis.

For visualization, I created three main visualizations:

A line chart showing the percentage of total CO2 emissions by year for the top countries selected using the Top N parameter.
A map at the country level showing CO2 emissions per capita for the year 2021.
A scatter plot comparing CO2 emissions and population at the country level, with bubbles sized by temperature change from CO2 for the year 2021. Additionally, I added a linear regression trend line for further analysis.
All three visualizations were colored using CO2 per capita and applied a divergent color scale for better interpretation.

Finally, I built an interactive dashboard to combine the visualizations and allow for user interaction. The dashboard included sheets showing the % of CO2 trend as a line chart, CO2 per capita as a map, and the relationships between CO2 and population as a scatter plot. I added a filter for country to allow users to explore specific countries, and ensured that the filter applied in-context to all sheets on the dashboard.

Through this project, meaningful insights were discovered regarding the global impact of CO2 emissions and trends. Some interesting patterns identified included the countries with the highest CO2 emissions, variations in CO2 emissions per capita across different regions, and the relationship between CO2 emissions, population, and temperature change. These insights can inform decision-making processes aimed at mitigating climate change and promoting sustainability efforts globally.
