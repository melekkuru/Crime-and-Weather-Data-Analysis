# Crime and Weather Data Analysis

This repository contains an analysis of crime and weather data for Colchester in 2023. The goal of this project is to explore the relationship between weather conditions and crime rates using data visualization and statistical methods.

---

## Overview

Understanding how weather impacts crime can provide valuable insights for city planning and law enforcement. This project leverages crime and weather datasets to uncover patterns and trends.

Key features of the project include:

- **Crime Data Analysis**: Examining crime patterns and distributions across various categories.
- **Weather Data Analysis**: Analyzing temperature and other weather variables.
- **Combined Analysis**: Identifying potential correlations or trends between weather conditions and crime rates.
- **Data Visualization**: Clear and informative visualizations to summarize the findings.

---

## Data Sources

- **Crime Data**: Contains detailed information about crimes reported in Colchester in 2023.
- **Weather Data**: Includes daily temperature records and weather conditions for the same period.

---

## Repository Structure

```plaintext
Crime-and-Weather-Data-Analysis/
├── data/
│   ├── crime23.csv         # Crime dataset
│   ├── temp2023.csv        # Weather dataset
├── analysis/
│   └── Crime_and_Weather_Analysis.Rmd # R Markdown file for analysis
├── results/
│   └── visualizations/     # Generated plots and visualizations
├── README.md               # Project description and instructions
└── requirements.txt        # Required R packages
```

---

## How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/melekkuru/Crime-and-Weather-Data-Analysis.git
cd Crime-and-Weather-Data-Analysis
```

### 2. Install Dependencies
Ensure you have **R** installed. Then, install the required R packages:
```R
install.packages(c("ggplot2", "dplyr", "lubridate", "tidyr", "readr"))
```

### 3. Run the Analysis
Open the R Markdown file in RStudio and knit it to produce a report:
```plaintext
analysis/Crime_and_Weather_Analysis.Rmd
```

---

## Key Findings

- **Crime Trends**: Analysis shows peaks in crime rates during specific weather conditions.
- **Weather Impact**: Identified correlations between temperature fluctuations and certain types of crime.
- **Insights**: Provides actionable insights for policymakers and law enforcement.

---

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization (ggplot2)
- Statistical Analysis
- R Markdown Reporting

---

