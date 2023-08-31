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

Our data analysis uncovered several significant insights into the relationship between weather conditions and public transportation ridership. Key findings include:

- There is a notable negative correlation between rainy days and public transportation ridership. Specifically, all public transport modes, except for the LRT system, exhibit a correlation coefficient of approximately -0.49. For the LRT system, the correlation coefficient is -0.46.

# Data Dictionary

For reference, here is a data dictionary providing descriptions of the columns in the ridership dataset:

| **Feature Name**   | **Data Type** | **Description**                                         |
|-------------------|---------------|---------------------------------------------------------|
| `month`           | Object (str)  | The month for which the ridership data is recorded.    |
| `no_of_rainy_days`| Integer       | The number of rainy days in the given month.           |
| `bus`             | Integer       | Total ridership for public buses in the month (in thousands).        |
| `mrt`             | Integer       | Total ridership for Mass Rapid Transit (MRT) in the month (in thousands). |
| `lrt`             | Integer       | Total ridership for Light Rail Transit (LRT) in the month (in thousands). |
| `total_ridership` | Integer       | The combined total ridership for all modes of transportation in the month (in thousands). |

# Visualization

![Stacked Bar Chart of Ridership by Month](/Generated%20images/Combined_Chart_with_Secondary_Axis_Labels.png)

Shows a scatterplot of number of rainy days imposed on the bar chart showing the various ridership numbers across a monthly period between January 2019 to August 2022.

![Ridership Bar Chart (normalized)](/Generated%20images/Combined_Chart_with_Percentages_Labels_(Normalized).png)

Shows a scatterplot of number of rainy days imposed on the normalized bar chart showing the various ridership numbers across a monthly period between January 2019 to August 2022 to account for the drastic drop in riderships.

# Conclusion and Recommendations

In conclusion, our analysis highlights a moderate negative relationship between rainy days and public transportation ridership. While this correlation suggests that rainy weather can influence ridership, it's essential to recognize that ridership is influenced by various factors.

## Recommendations

Based on our findings, we offer the following recommendations:

1. **Service Optimization:** Consider optimizing public transport services during rainy weather to accommodate potential increases in ridership. Ensure that buses and trains are well-maintained and have the capacity to handle higher passenger loads.

2. **Weather-Responsive Promotion:** Implement weather-responsive marketing campaigns to promote public transport as a reliable alternative during rainy periods. Highlight the advantages of avoiding traffic jams and reducing environmental impact.

3. **Data Integration:** Integrate weather data into transportation planning and scheduling. Real-time weather updates can help in managing service disruptions and delays more effectively.

4. **User Education:** Educate commuters about the benefits of using public transport during rainy days. Provide information on routes, schedules, and sheltered waiting areas to make public transport a convenient choice.

5. **Further Research:** Continue researching the interplay of factors affecting ridership, focusing on the impact of rainy weather. Explore whether additional factors like holidays and economic conditions influence ridership patterns.

By implementing these recommendations, public transportation authorities can enhance their services and promote ridership, especially during adverse weather conditions.

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

## External Sources for Interest

[https://www.sciencedirect.com/science/article/abs/pii/S0968090X16302492](https://www.sciencedirect.com/science/article/abs/pii/S0968090X16302492) (Zhou et al., 2017)

1. Zhou, M., Wang, D., Li, Q., Yue, Y., Tu, W., & Cao, R. (2017, February 1). Impacts of weather on public transport ridership: Results from mining data from different sources. Transportation Research Part C-emerging Technologies; Elsevier BV. [https://doi.org/10.1016/j.trc.2016.12.001](https://doi.org/10.1016/j.trc.2016.12.001)

While the document used seems to apply to the Shenzhen province of China, most of the means they have applied for that region can also be relevant to Singapore's climate and the ridership of various modes of transportation.

2. 
