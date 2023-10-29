# COVID-19 Pandemic Analysis: Does Income Affect Mortality Rate?

## Introduction
The COVID-19 pandemic was one of the deadliest disasters in U.S. history, ranking first with a death toll of over 1,000,000. While pandemics affect people regardless of wealth, they hit the poorest people the hardest. This one was no exception, as it had disrupted every area of the country’s healthcare system and had a devastating impact on poor and low-income communities. 

Based on A Poor People’s Pandemic Report in April 2022, people in poorer counties had died overall at almost twice the rate of those in richer counties. In an effort to better understand and support at-risk populations across America, we investigated how income had affected mortality rate during the pandemic at the county level.

## Libraries
- renv
- odbc
- tidyverse
- plotly
- RColorBrewer
- rjson

## Data
- The simplemaps United States Counties Database is an accurate and up-to-date database of United States counties built from authoritative sources such as the U.S. Census Bureau and the Bureau of Labor Statistics. The 2022 edition contained comprehensive census data for 3,234 counties with up to 78 fields as of May 13, 2022.
- Our own database had been tracking COVID-19 cases and deaths in the United States for 3,223 counties since the start of the pandemic on Jan 21, 2020.

## Analysis
- A scatterplot was created to view the relationship between median household income and COVID-19 mortality rate
- Linear correlation was calculated using the Pearson correlation coefficient
- A choropleth map of U.S. counties was created to geographically visualize this relationship 

## Results
- Observed a weak negative correlation between median household income and COVID-19 mortality rate with a Pearson correlation coefficient of -0.486 with p-value < 2.2e-16
- Low-income counties constituted 76.4% of total COVID-19 deaths  
- Among all counties with a high COVID-19 mortality rate, 97.54% were low-income
