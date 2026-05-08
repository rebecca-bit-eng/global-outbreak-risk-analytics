# global-outbreak-risk-analytics
![Outbreak Risk Visualization](Image4.png)
<div align="center">
  <img src="images/Image4.png" alt="Outbreak Risk Analytics" width="600px">
</div>
## Overview

This project explores global infectious disease vulnerability using country-level health and economic indicators from the World Bank. The analysis combines statistical modeling, clustering techniques, and epidemiological risk profiling to identify structural patterns associated with outbreak susceptibility across health systems.

The project was developed in R using a fully reproducible workflow in R Markdown.

---

## Objectives

- Develop a composite outbreak vulnerability risk framework
- Identify structural drivers of infectious disease vulnerability
- Cluster countries based on health system resilience profiles
- Assess statistical differences between health system groups
- Visualize global health disparities using data-driven methods

---

## Data Source

World Bank World Development Indicators (WDI)

Indicators used include:

- GDP per capita
- Health expenditure per capita
- Life expectancy
- Hospital bed availability
- Urban population percentage

Data were accessed directly through the `WDI` R package.

---

## Methods

The analysis includes:

### Data Processing
- Data extraction using the WDI API
- Cleaning and aggregation of country-level indicators
- Variable standardization for comparability

### Statistical Analysis
- Composite outbreak risk score construction
- K-means clustering
- ANOVA testing
- Tukey post-hoc comparisons
- Standardized linear regression modeling

### Visualization
- Cluster visualization
- Risk driver coefficient plots
- Global outbreak vulnerability mapping
- Interactive Plotly exploration

---

## Key Findings

- Countries with lower healthcare expenditure and weaker economic capacity consistently demonstrated higher outbreak vulnerability scores.
- Clustering analysis revealed clear separation between high-capacity and high-vulnerability health systems.
- Healthcare infrastructure indicators showed strong associations with outbreak preparedness and resilience.

---

## Tools & Technologies

- R
- R Markdown
- tidyverse
- ggplot2
- plotly
- WDI
- sf
- rnaturalearth

---

## Repository Structure

```text
global-outbreak-risk-analytics/
│
├── OI.Rmd          # Full reproducible R Markdown analysis
├── OI.html         # Rendered HTML report
├── OI.pdf          # Final project report
│
├── Image1
├── Image2
├── Image3
├── Image4
├── Image5
└── Image6
```

---

## Reproducibility

The project is fully reproducible through the included R Markdown workflow. Data are retrieved programmatically through the World Bank API.

---

## Author

Rebecca Rose  
BSc Biostatistics | Public Health Data Analytics
