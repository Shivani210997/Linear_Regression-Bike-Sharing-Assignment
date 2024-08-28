# BoomBikes|Bike-Sharing-Assignment
Model the demand for shared bikes using the provided variables. This will help the management, understand how demand varies with different factors and adjust 
strategies accordingly. The model will also aid in analyzing demand dynamics in new markets.

  ![BoomBike share](https://github.com/user-attachments/assets/f59d6155-559c-4d8c-8d77-be03ea6e2607)


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Recommendations](#recommendations)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)
* [Glossary](#glossary)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### General Information about the Project:
This project involves building a multiple linear regression model to predict the demand for shared bikes. The goal is to help BoomBikes, a US-based bike-sharing provider, understand the key factors influencing bike demand and to assist in formulating a strategic business plan post-pandemic for future growth.

### Problem Statement:
Develop a multiple linear regression model to predict the demand for shared bikes using the provided independent variables. This model will help BoomBikes understand the key factors influencing bike demand and optimize their business strategy post-pandemic and recover from the revenue declines caused by the pandemic.

### Project Background:
BoomBikes, a US bike-sharing provider, has recently faced significant revenue declines due to the ongoing COVID-19 pandemic. The challenging market conditions 
have made it difficult for the company to maintain operations. To swiftly boost their revenue, once the lockdown ends and the economy recovers, BoomBikes is 
developing a strategic business plan.

### Business Goal:
The project aims to solve the problem of predicting the demand for shared bikes using linear regression model with the available independent variable, enabling BoomBikes to anticipate customer needs and optimize their operations in a post-pandemic market. This understanding will help the company position itself competitively and increase revenue.

### Dataset that is being used:
The project uses a dataset collected from various meteorological surveys and consumer behavior studies. 
This dataset captures daily bike demand across the American market, along with factors influencing this demand, such as weather conditions and user demographics.

#### STEPS:
STEP 1: Data Understanding and Data Loading.
STEP 2: Data Pre-processing steps.
STEP 3: Data encoding and Mapping.
STEP 4: EDA 
STEP 5: Dummy Variables Creation.
STEP 6: Train and Test split.
STEP 7: Rescaling the Features.
STEP 8: Feature Selection
     a) Recurrsive festure elimination (Automated)
     b) Manual : VIF calculation or p-value
     c) Hybrid : using both Automated and then Manual.
STEP 10: Model building.
STEP 11: Evaluation on the Test data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used:
1. Name: matplotlib
   Version: 3.8.4
   Summary: Python plotting package
2. Name: seaborn
   Version: 0.13.2
   Summary: Statistical data visualization
3. Name: pandas
   Version: 2.2.2
   Summary: Powerful data structures for data analysis, time series, and statistics
4. Name: numpy
   Version: 1.26.4
   Summary: Fundamental package for array computing in Python
5. Name: plotly
   Version: 5.22.0
   Summary: An open-source, interactive data visualization library for Python.
6. Name: scikit-learn
   Version: 1.4.2
   Summary: A set of python modules for machine learning and data mining
7. Name: statsmodels
   Version: 0.14.2
   Summary: Statistical computations and models for Python

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Recommendations:
Cutoff/Threshold for p-value and VIF varies in real time scenario, there is no specific limit, however one can use standard threshold as,
1. p-value : < 0.05
2. VIF : <= 5

## Conclusions:
- The significant variables like temperature, year, windspeed, humidity, weather conditions, and seasons provide a strong basis for predicting and understanding the demand for shared bikes.
- 'weathersit_LightSnowRain' (-0.252275): This variable is significant, indicating that adverse weather conditions like light snow or rain significantly reduce bike demand.
- hum (-0.150414): Humidity also has a potential impact on bike demand. Higher humidity levels decrease the likelihood of people using bikes.
- windspeed (-0.177862): Wind speed negatively impacts bike demand, making it a significant predictor. Higher wind speeds lead to a decrease in bike usage.
- season_Spring (-0.100797): The season of spring has a negative impact, making it a significant predictor in reducing bike demand compared to other seasons.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Acknowledgements:
- This project was inspired by UpGrad IIITB Programme, as a Assignment for the EPGP in Machine Learning and Artificial Intelligence course.
- This project was based on building Multiple Linear Regression Model.

## Contact:
Created by [@Shivani210997] - feel free to contact me!

## License:
This project is open source and available without restrictions.

## Glossary:
MLR - Multiple Linear Regression.

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
