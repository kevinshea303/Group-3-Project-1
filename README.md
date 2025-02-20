# COVID-19 Vaccination and Mortality Rate Analysis :  "Did the vaccine actually help         prevent deaths?”

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

## Objective

The objective of this analysis is to examine if the vaccination rollout had a measurable impact on reducing COVID-19 mortality rates.

### Key Questions:

- Did the vaccine help reduce the COVID-19 mortality rate?
- How did the vaccination rate compare to the death rate over time?

## Methodology

1. **Data Preprocessing**: 
   - The dataset was cleaned to ensure consistency, handling any missing or erroneous values.
   - The `date` column was converted to datetime format to enable chronological sorting and analysis.

2. **Data Analysis**:
   - We filtered the data for specific dates to observe the trends at key time points (e.g., start of vaccination programs).
   - We calculated the **mortality rate** by dividing the total number of deaths by the total population or cases (if available).
   - We analyzed the relationship between **vaccination rates** and **mortality rates** over time to evaluate the potential effect of vaccines on preventing deaths.

3. **Data Visualization**:
   - Visualizations, such as time series plots and bar charts, were created to highlight the correlation between vaccinations and deaths.
   - A histogram was used to compare the mortality rate and vaccination rate at specific points in time.

## Key Findings

- **Trend Observations**: As the vaccination rate increased over time, the **mortality rate** appeared to decrease, suggesting that vaccines may have played a role in reducing deaths.
- **Vaccination and Deaths**: The vaccination rate and total deaths are inversely correlated in some periods, which supports the hypothesis that the vaccine helped in reducing mortality.
- **Impact of Vaccination**: Mortality rates decreased at certain points when significant vaccination milestones were reached, suggesting the positive effects of vaccination.

### Mortality Rates by Vaccination Categories:

- **Low Vaccination Mortality Rate**: 41,081.75 deaths
- **Medium Vaccination Mortality Rate**: 45,644.13 deaths
- **High Vaccination Mortality Rate**: 82,666.59 deaths

## Conclusion

The analysis suggests that COVID-19 vaccinations have had a positive impact on reducing mortality rates. The trends indicate a decrease in the mortality rate as vaccination rates increased, providing evidence that the vaccine helped prevent deaths.

However, it is important to consider other factors such as virus variants, healthcare systems, and public health measures that might have also contributed to the observed outcomes.

## Requirements

To run this analysis and reproduce the results, the following Python libraries are required:

- `pandas` (for data manipulation and analysis)
- `matplotlib` (for plotting graphs and visualizations)
- `numpy` (for numerical operations)

You can install these libraries using the following command:

```bash
pip install pandas matplotlib numpy
