# Bike Sharing Assignment
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

> In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

>  The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Table of Contents
* MLR_bike_sharing.ipynb(MLR model building ipynb file containing the entire process has comments)
* A bike-sharing MLR assignment questions.pdf(pdf containing answer to assignment questions)

### Summary of Variables Describing Bike Demand:

#### Weather-related Variables:
- **Temperature (temp)**: Temperature has a strong positive impact on bike demand, indicating that warmer weather encourages more bike rentals.
- **Weather Conditions (weathersit_Light Snow, weathersit_Mist)**: Light snow and misty conditions have significant negative impacts on bike demand, reducing rentals during adverse weather.

#### Seasonal and Monthly Variables:
- **Seasons (season_Summer, season_Winter)**: Both summer and winter seasons positively influence bike demand, with winter showing a slightly stronger impact. This suggests that favorable weather conditions in both seasons contribute to increased rentals.
- **Months (mnth_Aug, mnth_Sep)**: August and September exhibit significant positive impacts on bike demand. These months likely coincide with peak tourist seasons, favorable weather, or cultural events.

#### Temporal Variables:
- **Year (yr)**: Year shows a positive impact on bike demand, indicating a trend of increasing popularity or availability of bike-sharing services over time.
- **Weekday (weekday_Sun)**: Sundays have a negative impact on bike demand compared to other weekdays, possibly due to reduced commuting or leisure activities on weekends.

#### Other Factors:
- **Holiday**: Holidays negatively affect bike demand, suggesting fewer rentals during holiday periods.
- **Windspeed**: Higher windspeeds negatively impact bike demand, likely due to discomfort or safety concerns associated with windy conditions.

### Model Fit and Explanation:

- **R-squared (Adjusted R-squared)**: The model’s R-squared value of 0.840 (Adjusted R-squared: 0.836) indicates that approximately 84% of the variance in bike demand is explained by the included variables. This suggests that the model provides a robust framework for understanding and predicting bike rental patterns based on weather, seasonal variations, temporal factors, and specific days.
  
- **F-statistic**: The high F-statistic of 237.7 with a very low Prob (F-statistic) of 3.80e-190 confirms that the overall model is statistically significant. This means that the included variables collectively have a strong explanatory power in predicting bike demand.

### Conclusion:

The variables identified as significant in the regression model collectively describe and explain bike demand patterns effectively. They encompass a range of factors including weather conditions, seasonal variations, temporal trends, and specific days such as holidays and weekends. The model's high R-squared and significant F-statistic underscore its reliability in predicting bike rentals based on these influential variables.


## Technologies Used
- Python
- Matplotlib
- Numpy
- Pandas
- Seaborn
- sklearn
- statsmodels
  

## Contact
Created by [@kshitijD38] - feel free to contact me!
