# Rocketing Ahead: Leveraging Data Science in the New Space Age





<img align="left"  src="https://github.com/FotiouK/SpaceX_Data_Science/assets/108896534/0fcac09e-c66b-4fa5-9c43-6ce0e5e7367c" alt="image" height="300" >


## Overview
This repository forms part of the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) and focuses on predicting the success of SpaceX rocket launches. Utilising data collected through SpaceX's REST API and web scraping from Wikipedia, we've performed comprehensive data wrangling, exploratory data analysis (EDA), and predictive analytics.

<br>
<br>

## Purpose
SpaceX's groundbreaking ability to reuse the first stage of their Falcon 9 rockets has significantly lowered launch costs compared to other providers. With each Falcon 9 launch costing approximately 62 million dollars, accurate prediction of successful first stage landings becomes pivotal in estimating launch costs. This predictive capability holds immense value for competitors vying against SpaceX for rocket launches.
### Key Questions
- Can historical launch data effectively predict the success of new launches based on first stage landing outcomes?
- Is there a discernible pattern that maximizes the likelihood of a successful launch based on historical data analysis?

## Methodology

### Data Collection
- Utilized SpaceX REST API
- Conducted web scraping from Wikipedia

### Data Processing
- Performed extensive data wrangling to generate a landing class from the outcome column
- Conducted exploratory data analysis (EDA) using visualization techniques and SQL
<p align="center">
  <img src="https://github.com/FotiouK/SpaceX_Data_Science/assets/108896534/5c6a30fe-4c67-49df-a208-522dacbb44d5" alt="image">
</p>

- Utilized interactive visual analytics with Folium and Plotly Dash
![image](https://github.com/FotiouK/SpaceX_Data_Science/assets/108896534/708c8d66-5c56-49b0-b152-6b0de2e31159)

### Predictive Analysis
- Employed classification models to predict launch success
- Leveraged GridSearchCV to determine the best-fit model parameters
<p align="center">
  <img src="https://github.com/FotiouK/SpaceX_Data_Science/assets/108896534/799ba67d-4ce0-438d-8258-ebd28f365f70" alt="image" height="400">
</p>

## Repository Structure

### Jupyter Notebooks
1. [SpaceX API Data Collection](https://github.com/FotiouK/SpaceX_Data_Science/blob/main/1-jupyter-labs-spacex-data-collection-api.ipynb) 
2. [Web Scrapping Data Collection](https://github.com/FotiouK/SpaceX_Data_Science/blob/main/2-jupyter-labs-webscraping.ipynb)
3. [Data Wrangling](https://github.com/FotiouK/SpaceX_Data_Science/blob/main/3-jupyter-spacex-data-wrangling.ipynb) 
4. [Exploratory Analysis Using SQL](https://github.com/FotiouK/SpaceX_Data_Science/blob/main/4-jupyter-labs-eda-sql-coursera_sqllite.ipynb) 
5. [Exploratory Analysis Using Pandas and Matplotlib](https://github.com/FotiouK/SpaceX_Data_Science/blob/main/5-jupyter-labs-eda-dataviz.ipynb) 
6. [Interactive Visual Analytics with Folium](https://github.com/FotiouK/SpaceX_Data_Science/blob/main/6-jupyter_launch_site_location_folium.ipynb) 
7. [Interactive Dashboard with Ploty Dash](https://github.com/FotiouK/SpaceX_Data_Science/blob/main/7-spacex_dash_app.py.ipynb)
8. [Predictive Analysic (Classification)](https://github.com/FotiouK/SpaceX_Data_Science/blob/main/8-SpaceX_Machine_Learning_Prediction.ipynb)

### Presentation
- [Rocketing Ahead Presentation](https://github.com/FotiouK/SpaceX_Data_Science/blob/main/Rocketing%20Ahead%20Presentation.pdf)

## Conclusion
Through this project, we aim to provide insights into the predictability of successful rocket launches based on historical data. Our analysis delves into the potential impact of successful first stage landings on launch costs, offering valuable information for stakeholders in the space industry.

Feel free to explore the notebooks, visualizations, and models shared in this repository!
