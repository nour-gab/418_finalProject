# 📊 STA 518 Final Project — Demographics and U.S. Presidential Elections

This project explores the relationship between state-level demographic data and U.S. presidential election outcomes. We investigate how factors like income, education, and race correlate with the winning party in presidential elections across recent cycles (2008, 2012, and 2016).

## 👩‍💻 Authors

- Nour Gaboussa  
- Binju Karki  
- Sam Kiel  

## 🧠 Project Overview

Our goal was to assess whether certain demographic characteristics (e.g., median income, educational attainment, racial composition) can predict or explain voting trends in U.S. presidential elections. We used datasets from:

- 📊 **MIT Election Data and Science Lab (MEDSL)**: Voting results from 1976–2020.  
- 🧾 **U.S. Census Bureau**: Demographic data (2008–2023), such as income, education, and race.

## 🔧 Technologies Used

- **R**  
- `tidyverse`  
- `ggplot2`  
- `dplyr`  
- `leaflet`  
- `tidyr`  
- `janitor`  
- `skimr`

## 🧼 Data Cleaning & Preparation

We merged and cleaned multiple datasets across time periods, states, and formats using:
- Column standardization and type harmonization.
- Filtering data to relevant election years.
- Joining demographic and election data on state names.
- Creating a data dictionary and summary statistics for clarity.

## 📈 Key Analysis & Methods

- **Visualization**: 
  - Income distribution by party affiliation.
  - Education levels across Democrat vs. Republican states.
  - Racial demographic heatmaps using `leaflet`.

- **Statistical Inference**:  
  - Bootstrap confidence intervals for income and education.
  - Permutation testing to assess significance of group differences.

- **State-Level Exploration**:  
  - Case studies on states with shifting voting patterns.

## 🧠 Insights

- States with higher median income and college attainment tended to vote Democrat.
- Republican states generally had lower racial diversity and lower education levels.
- Statistically significant differences were found between party outcomes and several key demographic indicators.



