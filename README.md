# Data Overview

This project utilizes a dataset covering public transportation ridership data and weather conditions from January 2019 to August 2022. The data sources and scope are as follows:

## Public Transport Ridership Data

- **Data Source:** Land Transport Authority of Singapore
- **Time Period:** January 2019 to August 2022
- **Variables Analyzed:** Average Daily Ridership (‘000)
- **PDF Source:** [Link to PDF](https://www.lta.gov.sg/content/dam/ltagov/who_we_are/statistics_and_publications/statistics/pdf/PT_Ridership_Monthly_2019-2022.pdf)

For the most up-to-date and detailed information on the public transport ridership dataset, please refer to the [PDF source](https://www.lta.gov.sg/content/dam/ltagov/who_we_are/statistics_and_publications/statistics/pdf/PT_Ridership_Monthly_2019-2022.pdf) directly.

## Weather Data

- **Data Source:** `rainy_days_to_ridership.csv` (Derived from `rainfall-monthly-number-of-rain-days.csv` by adding the number of rainy days to each of its respective dates in the original CSV)
- **Time Period:** January 2019 to August 2022
- **Variables Analyzed:** 
  - `Date`: The date of the data entry
  - `Rainfall`: The monthly total rainfall

# Analysis Summary

Our data analysis revealed several important insights regarding the relationship between weather conditions and public transportation ridership. Key findings include:

- [Highlight your main findings here]

# Data Dictionary

For reference, here is a data dictionary providing descriptions of the dataset's columns:

- `Date`: The date of the data entry.
- `Rainfall`: The monthly total rainfall.

# Visualization

![Sample Bar Chart](/path/to/sample-bar-chart.png)

[Include a brief description of the visualization and how it relates to your analysis.]

# Conclusion and Recommendations

In conclusion, our analysis highlights the [reiterate main conclusions]. Based on these findings, we recommend [mention any recommendations or actions].

# Original Conclusion

In this section, we present our analysis of the relationship between rainy days and ridership in public transportation. Our objective was to determine whether there is a discernible impact of rainy weather on ridership levels. We utilized a combination of data visualization and statistical analysis to gain insights into this relationship.

## Data Visualization and Correlation Analysis

We began our analysis by visualizing the data using a heatmap to explore the correlation between rainy days and ridership. The heatmap displayed a correlation coefficient of approximately -0.49, indicating a moderate negative correlation between these variables.

## Interpreting the Correlation

The negative correlation suggests that, on average, an increase in the number of rainy days is associated with a decrease in ridership. However, it's important to note that this correlation, while statistically significant, is not exceptionally strong. It signifies that rainy weather may be one of several factors influencing ridership.

## Factors Beyond Rainy Days

Our analysis also revealed that ridership patterns are influenced by various factors beyond rainy days. Other variables, such as mode of transportation (bus, MRT, LRT), may have a more substantial impact on ridership trends. Additionally, events, holidays, and economic conditions can play significant roles.

## Seasonality and Geographic Variations

Although our dataset covers several years, we observed that seasonality and regional variations may have relatively limited effects on ridership in this national context. With nationwide data, we focused on overarching trends rather than localized fluctuations.

## Implications and Further Research

These findings have implications for transportation planning and resource allocation. Understanding the relationship between weather and ridership can aid in optimizing public transportation services during inclement weather conditions. However, further research is needed to explore the complex interplay of factors affecting ridership.

## Conclusion

In conclusion, our analysis provides insights into the relationship between rainy days and ridership in public transportation. While a negative correlation exists, it is not the sole determinant of ridership patterns. The influence of rainy weather is part of a multifaceted landscape of factors shaping ridership trends.

## External Source for Interest

Source used: [https://www.sciencedirect.com/science/article/abs/pii/S0968090X16302492](https://www.sciencedirect.com/science/article/abs/pii/S0968090X16302492) (Zhou et al., 2017)

Zhou, M., Wang, D., Li, Q., Yue, Y., Tu, W., & Cao, R. (2017, February 1). Impacts of weather on public transport ridership: Results from mining data from different sources. Transportation Research Part C-emerging Technologies; Elsevier BV. [https://doi.org/10.1016/j.trc.2016.12.001](https://doi.org/10.1016/j.trc.2016.12.001)

While the document used seems to apply to the Shenzhen province of China, most of the means they have applied for that region can also be relevant to Singapore's climate and the ridership of various modes of transportation.
