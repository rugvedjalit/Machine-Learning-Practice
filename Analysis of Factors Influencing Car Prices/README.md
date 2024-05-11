Geely Auto Car Price Prediction
===============================

Overview
--------

This repository contains the analysis and predictive modeling of car prices using the Geely Auto dataset. The purpose of this project is to identify factors that significantly influence car prices and to develop a regression model to predict car prices based on these factors.

Dataset
-------

The dataset used in this project is the "CarPrice\_Assignment.csv", which is a comprehensive dataset of different car models sold by the Geely Auto company. It includes various features of cars such as wheelbase, car length, car width, curb weight, engine size, horsepower, and miles per gallon in the city.

[Download the dataset here](https://www.kaggle.com/code/tanmoyx/car-price-prediction-geely-auto)

Features
--------

The features selected for predicting the car prices are:

*   **Wheelbase**: the distance between the front and rear wheels.
    
*   **CarLength**: length of the car.
    
*   **CarWidth**: width of the car.
    
*   **CurbWeight**: the weight of a car without occupants or baggage.
    
*   **EngineSize**: size of the car's engine.
    
*   **Horsepower**: the power output of the engine.
    
*   **CityMPG**: miles per gallon the car can achieve in urban driving.
    

Exploratory Data Analysis
-------------------------

We conducted an initial exploratory analysis to understand the relationship between the selected features and the car price. Pairplots were generated to visualize the relationships.

Model Development
-----------------

A Linear Regression model was developed using the selected features. The dataset was split into training (80%) and testing (20%) sets using a random state for reproducibility.

Results
-------

The Linear Regression model achieved the following performance:

*   **Mean Squared Error (MSE)**: 14546204.444105463
    
*   **R-squared**: 0.8157402640248119
    

This R-squared value suggests that approximately 81.57% of the variability in car prices can be explained using the model.

Usage
-----

To run the analysis yourself, ensure you have Python installed along with the following libraries:

*   pandas
    
*   sklearn
    
*   matplotlib
    
*   seaborn
    

Conclusion
----------

The analysis and model demonstrate the significant impact of physical dimensions and engine characteristics on the pricing of cars in the Geely Auto dataset. For further improvements, additional features and different types of models could be explored.

Contact
-------

For any additional questions or contributions to this project, please reach out via GitHub issues or pull requests.
