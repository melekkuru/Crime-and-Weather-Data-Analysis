# Crime-and-Weather-Data-Analysis-for-Colchester

## Project Overview

This project aims to analyze **crime** and **weather data** for **Colchester** in **2023**. By combining **crime records** and **weather data**, the objective is to understand how weather patterns correlate with crime rates. The analysis includes a variety of data visualizations to illustrate the relationship between temperature, precipitation, and crime incidents across the city.

### Objectives:
- **Examine the link between weather patterns and crime trends** in Colchester.
- **Analyze crime data** to identify key crime types and their distribution across different streets.
- **Visualize weather data** using various plots and explore correlations with crime rates.

## Datasets:

### 1. **Crime Data (crime23.csv):**
The **crime23.csv** dataset contains information about **street-level crime incidents** in Colchester for the year 2023. It includes various crime types, location details (latitude, longitude), and outcome status. 

- **Total Records**: 6,878 crime incidents.
- **Key Variables**: 
  - **category**: Crime type (e.g., violent crime, theft).
  - **date**: Date of the incident.
  - **location**: Street-level location details.

### 2. **Weather Data (temp2023.csv):**
The **temp2023.csv** dataset contains daily **climate data** collected from a weather station in Colchester. The data includes temperature, humidity, wind speed, and other weather conditions for each day in 2023.

- **Total Records**: 365 days of weather data.
- **Key Variables**: 
  - **TemperatureCAvg**: Average temperature for the day.
  - **Precmm**: Precipitation in millimeters.
  - **WindkmhInt**: Wind speed in km/h.
  - **SunD1h**: Sunshine duration in hours.

## Methods and Analysis:

1. **Data Preprocessing**:
   - Cleaned the **crime** dataset by removing missing values and irrelevant columns.
   - Handled missing data in the **weather** dataset by imputing values where necessary (e.g., replacing missing precipitation values with zero).

2. **Data Visualization**:
   - Created various plots to visualize the data, such as:
     - **Histogram**: For visualizing temperature distribution and daily crime count.
     - **Boxplot**: To analyze the relationship between crime levels and temperature.
     - **Scatter Plot**: To compare average temperatures with crime rates.
     - **Time Series Plot**: To analyze crime trends over the year.
     - **Correlation Plot**: To explore relationships between weather variables.

3. **Key Findings**:
   - **Correlation Analysis**: A weak positive correlation (0.24) was found between **temperature** and **crime rates**, suggesting that warmer temperatures may lead to a slight increase in crime.
   - **Crime Distribution**: High crime days tend to be warmer, with **violent crimes** being the most prevalent.
   - **Street-Level Crime**: Certain streets in Colchester have higher crime rates, with **Blackene Gardens**, **Church Street**, and **Cowdray Avenue** showing notable spikes.

4. **Advanced Features**:
   - Created an **interactive map** using **leaflet** to visualize crime distributions across different categories (e.g., **violent crime**, **shoplifting**, etc.) on a map of Colchester.

## How to Use:

### Prerequisites:
Ensure you have **R** and the necessary libraries installed. The libraries required include:
- **ggplot2** for plotting.
- **dplyr** for data manipulation.
- **leaflet** for interactive maps.
- **xts** for time-series analysis.

### Running the Code:
1. Clone the repository:
   ```bash
   git clone https://github.com/melekkr/Crime-and-Weather-Data-Analysis-for-Colchester.git
