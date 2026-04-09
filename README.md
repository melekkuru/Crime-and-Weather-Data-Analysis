# Crime and Weather Data Analysis — Colchester 2023

Exploring the relationship between crime patterns and weather conditions in Colchester using data visualization and statistical analysis in R.

> Developed as part of the **Data Visualization (MA304)** module at the University of Essex.

---

## Overview

Understanding how weather influences crime can provide valuable insights for city planning and law enforcement. This project combines two datasets — police-reported crime records and daily temperature data for Colchester in 2023 — to uncover patterns, trends, and potential correlations.

**The analysis covers:**
- Crime distribution across categories and time periods
- Temperature trends and seasonal patterns
- Combined analysis of weather conditions vs. crime rates
- Interactive and static visualizations to communicate findings

---

## Data sources

| Dataset | Description | File |
|---------|-------------|------|
| Crime data | Crimes reported in Colchester, 2023 | `DATA/crime23.csv` |
| Weather data | Daily temperature records, 2023 | `DATA/temp2023.csv` |

---

## Key findings

- Crime rates show seasonal variation with peaks during warmer months
- Certain crime categories are more sensitive to temperature changes
- Correlation analysis reveals statistically significant relationships between weather and specific crime types
- Interactive visualizations provide drill-down capability for detailed exploration

---

## Project structure

```
Crime-and-Weather-Data-Analysis/
├── DATA/
│   ├── crime23.csv
│   └── temp2023.csv
├── Crime and Weather Data Analysis for Colchester.Rmd
├── requirements.txt
└── README.md
```

---

## Getting started

**Prerequisites:** R (4.0+) and RStudio

```r
# Install required packages
install.packages(c("ggplot2", "dplyr", "lubridate", "tidyr", "plotly",
                   "ggcorrplot", "ggthemes", "zoo", "xts", "knitr"))
```

Open `Crime and Weather Data Analysis for Colchester.Rmd` in RStudio and knit to produce the report.

---

## Technologies

R · ggplot2 · Plotly · dplyr · tidyr · R Markdown

---

## License

This project is for educational purposes. Feel free to use it as a reference.
