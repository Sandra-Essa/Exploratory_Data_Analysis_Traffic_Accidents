# Comprehensive Analysis of Traffic Accidents: Insights and Trends

- [Description](#description)
- [Dataset](#Dataset)
- [Methodology](#Methodology)
- [Key_Insights](#Key_Insights)
- [Tools](#Tools)


## Description

- This project delves into a comprehensive analysis of traffic accidents using a large dataset spanning multiple years. The dataset includes crucial information such as accident severity, start and end times, geographical coordinates, weather conditions, and more. By leveraging data analysis techniques and visualization tools, this project aims to uncover valuable insights into accident trends, their distribution across different locations and times, and factors influencing accident severity.

1) Analyze the frequency of traffic accidents in various cities and states.
2) Identify patterns and trends in accident occurrence based on time factors such as hour, day of the week, and month.
3) Investigate the relationship between weather conditions and accident rates.
4) Explore geographical hotspots of accidents using interactive maps and heatmaps.
5) Assess the severity of accidents and its impact on traffic flow.


## Dataset

- This dataset offers a comprehensive view of car accidents across 49 states in the USA, spanning from February 2016 to March 2023. The data collection process involved utilizing multiple APIs that stream traffic incident data. These APIs sourced information from diverse entities such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and road network sensors. As of now, the dataset encompasses around 7.7 million accident records.
- Dataset's Link: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

##  Methodology

1) Data Collection: The project utilizes a comprehensive dataset containing detailed information about traffic accidents, including location coordinates, timestamps, severity levels, weather conditions, and more.
2) Data Cleaning and Preprocessing: The dataset undergoes thorough cleaning to handle missing values, standardize formats, and prepare it for analysis.
3) Exploratory Data Analysis (EDA): Various statistical and visual analysis techniques are applied to extract meaningful insights from the data. This includes histograms, scatter plots, correlation matrices, and geographical visualizations.
4) Time Analysis: The project analyzes accident frequency based on temporal factors such as hour of the day, day of the week, and month of the year. This helps identify peak times for accidents and potential patterns.
5) Geographical Analysis: Through interactive maps and heatmaps, the project visualizes accident hotspots and identifies regions with high accident rates.
6) Severity Assessment: The severity of accidents is assessed based on the impact on traffic flow, providing insights into the most critical incidents.

## Key_Insights:

1) A minority, comprising less than 8% of all cities, experience an annual accident count surpassing 1000 incidents, highlighting that the majority of cities have a relatively low accident frequency.
2) New York lacks available accident data within the dataset, presenting a gap in the information landscape.
3) Over a thousand cities have recorded just one accident each, showcasing a widespread trend of minimal accident occurrences across numerous locations.
4) The distribution of accidents per city demonstrates an exponential decrease, indicating that a small number of cities bear the brunt of a high accident rate, while most cities experience considerably fewer accidents.
5) A significant surge in accident rates is observed during the morning rush hours, between 6 am to 10 am, suggesting a correlation with people hurrying to their workplaces or morning commute activities.
6) Similarly, the afternoon rush hours, from 3 pm to 6 pm, witness another peak in accident occurrences, attributed to commuters returning home or engaging in evening travel.
7) Weekends witness a notable concentration of accidents between 1 pm to 3 pm, possibly reflecting relaxed traffic conditions leading to increased accident-prone behavior.
8) September emerges as a month with a heightened incidence of accidents, indicating potential seasonal factors or behavioral patterns influencing road safety.
9) California stands out with the highest number of accidents among all states, underscoring significant traffic safety challenges within the region.
10) Despite expectations, most accidents occur under fair weather conditions, suggesting that adverse weather may not strongly correlate with increased accident rates, challenging common assumptions about weather-related accident risks.
11) Within cities, Miami reports the largest number of accidents, emphasizing localized traffic safety concerns within this urban area.


## Tools

1. Python
2. Jupyter Notebook
3. Libraries: Pandas, Numpy, Matplotlib, Seaborn.
