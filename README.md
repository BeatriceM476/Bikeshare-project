# Bike Sharing in Washington DC: Why increase Capital Bikeshare's financing for Ward 8?

## 📌 Project Overview
This project analyzes Washington DC's Capital Bikeshare (CBS) data from 2021 to 2023 to explore usage patterns, station performance, and socio-demographic correlations.  
It aims to provide data-driven insights to support strategic decisions, particularly regarding financing and accessibility improvements in Ward 8.

## 📄 Project Presentation
[![Project Presentation](./images/presentation_preview.png)](./docs/Capital_Bikeshare_presentation.pdf)  
👉 Click on the image or [here](./docs/Capital_Bikeshare_presentation.pdf) to view the full project presentation (PDF).

## 🚴 Bike Sharing Goals
- To address traffic congestion  
- To promote sustainable transportation  
- To encourage physical activity  
- To enhance tourism  
- To improve accessibility  

## 📊 Key Insights (examples)
- Usage patterns vary significantly by day, hour, and bike type.  
- Certain stations, particularly in Ward 8, are underutilized and could benefit from additional funding.  
- Socio-demographic factors such as population density, median age, income, and public transit usage correlate with bike usage.  

## 📊 Data Sources
- **Capital Bikeshare Full Data (2021–2023)**: 13 features including ride_id, bike type, start/end station, coordinates, and user type.  
- **Census Reporter 2023**: 10 features including population, median age, income, poverty rate, housing, education, and foreign-born population.  
- **Open Data DC – Wards (2022)**: Ward geometries for spatial analysis.

## 📊 Visualizations
![Social comparison between Ward 3 and Ward 8.](./images/05_Social_comparison_Ward3_Ward8.png)

![Average Ride Duration by Hour and Season](./images/09_Duration_Hours_Season.png)

![Poverty Rate vs. Bike Stations in Washington DC Wards](./images/14_Poverty_Bike_Stations_2022.png)

![Bike Use and Social Indicators by Ward](./images/15_Rides_Social_indicators.png)

![Modes of Transportation to Work by Ward in Washington DC](./images/16_Transportation_work.png)

## 🗺️ Interactive Map
[![Interactive Map Screenshot](./images/map_preview.png)](https://beatricem476.github.io/Bikeshare-project/dc_wards_map.html)  
👉 Click on the image or [here](https://beatricem476.github.io/Bikeshare-project/dc_wards_map.html) to explore the full interactive map.

## 🤖 Machine Learning Model
![Polynomial Ridge Regression](./images/19_polynomial_ridge.png)  
*Polynomial Ridge Regression (Degree 4), $R^2 = 85.16\%$*

## 🛠️ Tools & Methods
- **Languages & Libraries**: Python (Pandas, NumPy, Matplotlib, Seaborn), SQL  
- **Visualization**: Tableau, Jupyter Notebook  
- **Techniques**: Data cleaning, exploratory data analysis, geospatial mapping, KPI evaluation, dashboard design
