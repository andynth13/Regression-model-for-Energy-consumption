# Energy consumption in Steel industry
Regression model to predict the amount of energy usage

##  Introduction

This company produces several types of coils, steel plates, and iron plates. The information on electricity consumption is held in a cloud-based system. The information on energy consumption of the industry is stored on the website of the Korea Electric Power Corporation (pccs.kepco.go.kr), and the perspectives on daily, monthly, and annual data are calculated and shown.

## Dataset
The data was downloaded with some modification from [Kaggle Steel industry Energy consumption](https://www.kaggle.com/datasets/csafrit2/steel-industry-energy-consumption/ "Kaggle link").

Attribute Information:

Date Continuous-time data taken on the first of the month

Usage_kWh Industry Energy Consumption Continuous kWh

Lagging Current reactive power Continuous kVarh

Leading Current reactive power Continuous kVarh

CO2 Continuous ppm

NSM Number of Seconds from midnight Continuous S

Week status Categorical (Weekend (0) or a Weekday(1))

Day of week Categorical Sunday, Monday : Saturday

Load Type Categorical Light Load, Medium Load, Maximum Load


## Project goal

**1. Perform EDA and checking for cross correlation in the dataset**

**2. Use SGD Regressor with k cross fold to build a prediction model**

Try to optimize the model with Elasticet net and  other hyper parameters


## Acknowledgements
This dataset is sourced from the UCI Machine Learning Repository
Relevant Papers:

Sathishkumar V E, Changsun Shin, Youngyun Cho, Efficient energy consumption prediction model for a data analytic-enabled industry building in a smart city, Building Research & Information, Vol. 49. no. 1, pp. 127-143, 2021.

Sathishkumar V E, Myeongbae Lee, Jonghyun Lim, Yubin Kim, Changsun Shin, Jangwoo Park, Yongyun Cho, â€œAn Energy Consumption Prediction Model for Smart Factory using Data Mining Algorithms KIPS Transactions on Software and Data Engineering, Vol. 9, no. 5, pp. 153-160, 2020.

Transactions on Software and Data Engineering, Vol. 9, no. 5, pp. 153-160, 2020.

Sathishkumar V E, Jonghyun Lim, Myeongbae Lee, Yongyun Cho, Jangwoo Park, Changsun Shin, and Yongyun Cho, â€œIndustry Energy Consumption Prediction Using Data Mining Techniques, International Journal of Energy Information and Communications, Vol. 11, no. 1, pp. 7-14, 2020.

