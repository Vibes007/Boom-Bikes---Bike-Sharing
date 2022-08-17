# Bike Sharing Case Study
Bike sharing system is a shared transport service, in which bikes are made available for shared use to a individuals on a short term basis for a price or fee. A US bike sharing provider BoomBikes recently sufferered from revenue dips due to the ongoing corona pandemic.Because of the unexpected loss, the company is finding it difficult to sustain in the current market scenario. so it has decided to come up with the mindful business plan so that they can able to accelerate their revenue once the pandemic comes to an end and also boost the economy. This case study aims to provide us about the factors that influence the demand of bikes.


## Table of Contents
* [General Info](#general-information)
* [Structure of case study](#Structureofcasestudy)
* [Conclusions](#conclusions)
* [Final report](#Finalreport)
* [Technologies used](#Technologiesused)
* [Acknowledgements](#Acknowledgements)
* [References](#References) 
* [contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company BoomBikes specifically need to understand the factors affecting the demand of the shared bikes. They wants to find:

   - Which variables are significant in predicting the demand of the shared bikes
   - How well the variables describe the demand of the shared bikes
   
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demand varies with different features.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

# Structure of case study
 - Problem statement
 - Business objectives
 - Data understanding
 - Data preparation
 - Data visualization
 - Model building
 - Model selection
 - Residual analysis
 - Model evaluation
 - Final report

## Conclusions
 - The distribution of the counts is almost normally distributed.
 - On average around 4500 customers utilizing the bike service per day.
 - The usage of bike is less on sundays.
 - The usage of bike is more on thursday and friday.
 - When there is light snow, light rain, thunderstorm the number of bike users decreases.
 - When there is heavy rain, ice pallets, snow and fog, no one uses the bike.
 - The number of users were increased by 2019 with significant increase.
 - The number of bike users are less on holidays.
 - The number of counts is very less on january month.
 - Most counts are in the month june to sep.
 - The number of bike users in spring is very low.
 - The count has increased significantly in 2019.
 - The count is less on holidays
 - *he count is less on sundays
 - The number of bike users are more in clear, few clouds climate.
 - From the distribution of part_month it is evident that in the third half the count is less.
 - In the middle of the year the count is increasing. and in the first quarter of the year the count is vey less.
 - There is high positive correlation between temperature and count.
 - There is negative correlation between count and windspeed.
 - Humidity and windspeed are negatively correlated.
 - There is high positive correlation between temperature and count
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Final Report
Final Report As per our final model. the top three features for predicting the dependent variable i.e factor influencing the demand of the booking are:

 - Wind chill (derived variable from temperature and wind speed): Have coefficient value of '0.5028', which indicates that a unit increase in wind chill variable increases the bike hire numbers by 0.5028 units.

 - Weather_3 (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds): Have coefficient value of '-0.2810', which indicates that a unit increase in weather_3 decreases the bike hire numbers by 0.2810 units.

 - Year_2019: Have coefficient value of '0.2425', which indicates that a unit increase in year variable increases the bike hire number by 0.2425 units.

So it is suggested to give utmost important for the above said top three factors that affect the demand of the bike. Apart from these top three factors, there are some more variable on which the bike demand is depends on, and they are:

 - Season_spring Have coefficient value of '-0.1174'

 - Weather_2 Have coefficient value of '-0.0788'

 - Month_Jul Have coefficient value of '-0.0663'

 - Month_Sep Have coefficient value of '0.0646'

 - Season_winter Have coefficient value of '0.0564'

 - Workingday_1 Have coefficient value of '0.0331'

## Technologies Used
 - Python version 3.8.8
 - numpy library version 1.20.1
 - pandas library version 1.2.4
 - matplotlib library version 3.3.4
 - seaborn library version 0.11.1
 - scikit-learn library version 0.24.1
 - statsmodels version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by Upgrad Classes


## References
- https://www.kaggle.com/gauravduttakiit/bike-sharing-multiple-linear-regression
- https://towardsdatascience.com/end-to-end-case-study-bike-sharing-demand-dataset-53201926c8db
- https://rstudio-pubs-static.s3.amazonaws.com/387724_1f220f850a164604ae94d6dd4be1258a.html


## Contact
Created by [(https://github.com/Vibes007)] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
