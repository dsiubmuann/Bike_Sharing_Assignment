# Shared Bikes Demand Prediction
> This assignment is a programming assignment wherein we built a multiple linear regression model for the prediction of demand for shared bikes. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement:
A US bike-sharing provider BoomBikes has a daily dataset on the rental bikes based on various environmental and seasonal settings. It wishes to use this data to understand the factors affecting the demand for these shared bikes in the American market and come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown due to corona pandemic comes to an end.

* Requirements of the company :

        - Which variables are significant in predicting the demand for shared bikes.
        - How well those variables describe the bike demands

- Business Goal:
Its required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

- The Dataset being used : https://ml-course2-upgrad.s3.amazonaws.com/Linear+Regression+Assignment/Bike+Sharing+Assignment/day.csv

- The Data Dictionary used : https://drive.google.com/file/d/1x4Vi_FF0DEmTN1Cf6BnPHUuQP9p0s0Pz/view?usp=sharing

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- 1. Data understanding :
         Performed steps to check different aspects of the given dataset such as; shape, size, info, description, rows, columns, null values, changing or replacing some values for better readability.
- 2. Data Visualisation : 
        Plotted different important plots for better visualisation of the data we understood using matplotlib and seaborn libraries. We have also visualised Categorical Variables using Boxplot and Numeric Variables using Pairplot. Also used heatmap to check out better correlation.
- 3. Data Preparation:
        For preparation of data for building model, first dummy variables were created and then unnecessary columns were dropped.
- 4. Model Building : 
        - First performed train-test-split
        - Used Scaling method such as MinMaxScaler to scale the columns for better interpretability
        - Divided the whole dataset into X and y sets for model building
        - Built the first model with all the features which resulted, an Adjusted R-squared value of 84.2% which seems pretty good.
        - Model Building Using Recursive Feature Elimination (RFE)

- We performed Residual analysis before making the prediction on the test set i.e. finding the Error Terms
- finally, did the Model evaluation by plotting the graph between the `Actual` and the `Predicted values`

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - Version : 1.2.4
- numpy - Version : 1.20.1
- seaborn - Version : 0.11.1
- matplotlib - Version : 3.3.4
- statsmodels - Version : 0.12.2
- sklearn - Version :0.24.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@dsiubmuann] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->