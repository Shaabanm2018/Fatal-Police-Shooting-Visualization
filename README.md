# Project Overview
This repository hosts a data visualization project that explores fatal police shootings in the United States from 2015 to 2021. The project uses interactive visualizations to provide insights into the distribution of cases across states, breakdowns by race, weapon usage, age, and fleeing approaches.

# Data
The row data includes information such as:
States
City
Date
Gender
Age
Body camera
Manner of deaths (e.g., shot & tasered)
Armed (e.g., gun, knife, vehicle, etc.)
Race (e.g., white, black, Asian, etc.)
Mental health (presence of signs of mental illness)
Threat level (e.g., attack, steal, etc.)
Flee approach (e.g., car, foot, not fleeing, etc.)
Longitude & Latitude

# Visualizations
## 1. US Choropleth and Sankey
- The choropleth map displays the intensity of cases in each state, with tooltips showing total cases.
- Clicking on a state zooms in and displays a Sankey chart depicting the breakdown of cases by race.
![map1](https://github.com/Shaabanm2018/Fatal-Police-Shooting-Visualization/assets/76607364/1f260821-26ce-4419-bb5d-fa89ea0a5922)
![map2](https://github.com/Shaabanm2018/Fatal-Police-Shooting-Visualization/assets/76607364/c6198994-a83d-402c-b8a2-9dc577c84349)

## 2. Weapon Fatality Bubble Chart
- Interactive bubble chart showing cases per weapon, with bubble size representing total cases.
- Hovering over bubbles reveals a tooltip with weapon details.
- Clicking on a bubble displays a bar chart showing the distribution of fatalities for that weapon by gender.
- Hovering over bars in the bar chart displays tooltips with gender-specific details.
- Clicking on a bar in the bar chart shows another bar chart displaying the distribution of mental conditions for the selected gender.
![vis2](https://github.com/Shaabanm2018/Fatal-Police-Shooting-Visualization/assets/76607364/a983c62a-da3e-401c-a748-bba24c53fd3c)


## 3. Age Distribution Visualization
- Interactive visualization displaying fatalities distribution by age.
- Hovering over dots reveals a tooltip with age and total case information.
![Vis3](https://github.com/Shaabanm2018/Fatal-Police-Shooting-Visualization/assets/76607364/eb35d1c7-c46f-42c0-b3eb-c271e0c9c4db)


# 4. Race Distribution Visualization
- Bar chart displaying the distribution of fatalities per race.
- Hovering over bars shows horizontal lines extending to the y-axis for precise values.
- Clicking on any race bar reveals another bar chart showing fatalities distribution by fleeing approaches.
- Hovering over bars in the second bar chart displays tooltips with flee approach and case information.
![Vis4](https://github.com/Shaabanm2018/Fatal-Police-Shooting-Visualization/assets/76607364/70250456-f51c-44dc-be63-a3269e51b7eb)


# Technologies Used
- Visualization Libraries: (e.g., D3.js, Plotly)
- Programming Language: (e.g., Python, JavaScript)
- Other Dependencies: (list any additional libraries or tools)

# Getting Started
Clone the repository: git clone https://github.com/Shaabanm2018/Fatal-Police-Shooting-Visualization.git
Follow the setup instructions in the documentation.

# Usage
- Open the application.
- Explore the interactive visualizations.
  
# Contributing
Contributions are welcome.

# License
This project is licensed under the MIT License.
