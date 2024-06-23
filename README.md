# Bike Sharing Assignment

## Overview

The bike-sharing system allows individuals to rent bikes on a short-term basis, typically from automated stations. BoomBikes, a US provider, has seen revenue declines due to COVID-19. To prepare for recovery, BoomBikes aims to predict post-lockdown bike demand and optimize operations.

## Objectives

BoomBikes seeks answers to:

- Identify key predictors of bike demand.
- Assess the predictive power of these variables.

## Table of Contents

- **MLR_bike_sharing.ipynb**: Jupyter Notebook detailing the MLR model building process with comments.
- **A bike-sharing MLR assignment questions.pdf**: PDF containing answers to assignment questions.

## Key Predictors of Bike Demand

### Weather-related Variables:
- **Temperature (temp)**: Positive correlation with bike rentals, indicating higher demand in warmer weather.
- **Weather Conditions (weathersit_Light Snow, weathersit_Mist)**: Negative impact on bike demand during light snow or misty conditions.

### Seasonal and Monthly Variables:
- **Seasons (season_Summer, season_Winter)**: Increased rentals during both summer and winter, with winter showing stronger impact.
- **Months (mnth_Aug, mnth_Sep)**: Significant bike demand in August and September, possibly due to favorable weather and cultural events.

### Temporal Variables:
- **Year (yr)**: Increasing trend in bike demand over time.
- **Weekday (weekday_Sun)**: Decreased rentals on Sundays compared to weekdays.

### Other Factors:
- **Holiday**: Reduced bike demand on holidays.
- **Windspeed**: Negative impact on bike rentals during higher windspeeds.

## Model Fit and Explanation

- **R-squared (Adjusted R-squared)**: 0.840 (0.836 adjusted), indicating 84% variance explained by the model.
- **F-statistic**: 237.7 with Prob (F-statistic) < 0.001, confirming model significance in predicting bike demand.

## Conclusion

The regression model effectively explains bike demand variations using weather, seasonal, temporal, and other relevant factors. It provides BoomBikes with insights to optimize operations post-pandemic and enhance revenue.

## Technologies Used

- Python
- Matplotlib
- Numpy
- Pandas
- Seaborn
- scikit-learn
- statsmodels

## Contact

Created by [@kshitijD38] - feel free to contact me!
