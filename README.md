# COVID-19 Vaccination and Mortality Rate Analysis

## Overview

This project explores the impact of COVID-19 vaccination on mortality rates. The analysis aims to investigate whether the vaccine helped prevent deaths by comparing the trends of vaccination rates and death rates over time.

## Data Source

The data used for this analysis was sourced from [Kaggle's COVID-19 dataset](https://www.kaggle.com/datasets/patricklford/covid-19). The dataset contains time-series data on COVID-19 vaccinations and deaths worldwide, including information on total vaccinations administered, total deaths, and daily changes.

### Data File

The dataset is available as a CSV file and includes the following columns:

- **date**: The date of the record.
- **total_vaccinations**: The cumulative total number of vaccinations administered by the date.
- **total_deaths**: The cumulative total number of deaths attributed to COVID-19 by the date.
- **mortality_rate**: The mortality rate calculated as the ratio of deaths to total cases or population (if applicable).
- **vaccination_change**: The change in the number of vaccinations between consecutive days.
- **death_change**: The change in the number of deaths between consecutive days.

## Key Questions

### 1. Did the vaccine help reduce the COVID-19 mortality rate?  
This question is central to understanding whether the introduction of vaccines had a significant impact on reducing deaths due to COVID-19.

### 2. How did the number of COVID-19 cases change over time across different countries?  
This question examines how the pandemic evolved across various countries. Did the number of cases vary, and how did vaccination efforts affect the course of the pandemic?

### 3. What group of people are the most at risk?  
This question looks at which groups, such as age, gender, and health conditions, were most vulnerable to severe outcomes from COVID-19.

### 4. How were vaccinations distributed globally, and how does vaccination coverage compare by country?  
This question investigates the global distribution of vaccines and the disparities between countries in terms of vaccination coverage.

### 5.How did mental health trends change during the pandemic?
This question explores the psychological effects of COVID-19, such as the rise in anxiety and depression during lockdowns, economic disruptions, and fears related to the virus. It also considers which demographic groups were most affected by these changes, with a focus on young adults and vulnerable populations. Was there a correlation between COVID-19 cases and mental health crises?



## Objective

The objective of this analysis is to examine if the vaccination rollout had a measurable impact on reducing COVID-19 mortality rates.

### Key Findings:

- **Trend Observations**: As the vaccination rate increased over time, the **mortality rate** appeared to decrease, suggesting that vaccines may have played a role in reducing deaths.
- **Vaccination and Deaths**: The vaccination rate and total deaths are inversely correlated in some periods, which supports the hypothesis that the vaccine helped in reducing mortality.
- **Impact of Vaccination**: Mortality rates decreased at certain points when significant vaccination milestones were reached, suggesting the positive effects of vaccination.
- **Mental Health Impact: During the pandemic, mental health symptoms, especially anxiety and depression, rose significantly, particularly among young adults (ages 18-29). Factors such as social isolation, economic uncertainty, and disruptions to daily life played a role in the mental health crisis. Although there was a weak correlation between COVID-19 deaths and mental health crises, it was clear that the broader societal changes due to the pandemic had a profound effect on mental well-being.

### Mortality Rates by Vaccination Categories:

- **Low Vaccination Mortality Rate**: 41,081.75 deaths
- **Medium Vaccination Mortality Rate**: 45,644.13 deaths
- **High Vaccination Mortality Rate**: 82,666.59 deaths

## Conclusion

The analysis suggests that COVID-19 vaccinations have had a positive impact on reducing mortality rates. The trends indicate a decrease in the mortality rate as vaccination rates increased, providing evidence that the vaccine helped prevent deaths.

However, it is important to consider other factors such as virus variants, healthcare systems, and public health measures that might have also contributed to the observed outcomes. Additionally, the pandemic's psychological toll, particularly among younger populations, underscores the need for mental health interventions in future global crises.
The analysis suggests that COVID-19 vaccinations have had a positive impact on reducing mortality rates. The trends indicate a decrease in the mortality rate as vaccination rates increased, providing evidence that the vaccine helped prevent deaths.

 


## Requirements

To run this analysis and reproduce the results, the following Python libraries are required:

- `pandas` (for data manipulation and analysis)
- `matplotlib` (for plotting graphs and visualizations)
- `numpy` (for numerical operations)

You can install these libraries using the following command:

```bash
pip install pandas matplotlib numpy
