## upGrad-BoomBike-CaseStudy_BalkrishnanV_27Nov2024
========================================================================
# BoomBike Case Study


## Table of Contents
* [General Info](#general-information)
* [Libraries Used](#technologies-used)
* [Some inferences from the BoomBike data analysis](#inferences)
* [Acknowledgements](#acknowledgements)

## General Information
- Provide general information about your project here.
  >> This project is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes. 
- What is the background of your project?
  >> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
  >> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
  >> In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
  >> They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.
  >> The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
- What is the business probem that your project is trying to solve?
  >>We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Libraries Used
- Pandas
- Seaborn
- Matplotlib
- sklearn (train_test_split; MinMaxScaler; r2_score; RFE; LinearRegression)
- statsmodels.api (variance_inflation_factor)

## Some inferences from the BoomBike data analysis
>> BoomBike demand is lowest in Spring season (median value ~2000).

>> BoomBike demand is highest in Fall season (median value ~5500).

>> BoomBike demand in 2019-year is higher than that in 2018-year (median value difference of ~2000)

>> Between months APR to OCT the BoomBike demand is high.

>> BoomBike demand is lowest in JAN month (median value ~2000).

>> Throughout the weekdays the demand for BoomBike has approximately similar median values.

>> BoomBike demand is very similar in working days and holidays.

>> BoomBike demand is lowest (with median value of ~2000) when weather conditions are Light Snow / Light Rain Thunderstorm Scattered Clouds / Light Rain Scattered Clouds.


## Acknowledgements
- This project was proposed by [upgrad.com](https://learn.upgrad.com/course/5810/segment/56042/334812/1013171/5064649).

## Contact
Created by [balkrishnan.venkiteswaran@gmail.com] - feel free to contact me!


## License
This project is open source and available under the [MIT License](https://github.com/balkrishnan/upGrad-BoomBike-CaseStudy_BalkrishnanV_27Nov2024/blob/main/LICENSE).

