# Pollution-prediction-system


[![](https://img.shields.io/badge/Made_with-Python3-red?style=for-the-badge&logo=python)](https://www.python.org/ "Python3")
[![](https://img.shields.io/badge/Made_with-Keras-red?style=for-the-badge&logo=keras)](https://www.python.org/ "Python3")
[![](https://img.shields.io/badge/Made_with-Scikit_Learn-red?style=for-the-badge&logo=scikit-learn)](https://www.vue.js/ "Vue.js")


# Overview
Pollution prediction is the practice of predicting the value of air pollutants for a given location based on different weather parameters. Pollution prediction is done by gathering data about the current state of the atmosphere. Pollution information is essential in every facet of life like agriculture, tourism, airport system, mining industry, and power generation. Hence, prediction pollution adequately is very necessary, here we are using different supervised machine learning techniques to process datasets that can learn and make predictions more effectively based on basic weather information. The pollution prediction system is modeled as a regression problem that is for different weather parameters, finding a continuous value of pollutants over time. A lot of factors affecting the pollutants were hidden, which were extracted to improve the prediction of pollutants.

------------------------------------------

# Data


The dataset used in this project provides the value of pollutants based on basic weather information (temperature and humidity) 
and the input values of 5 sensors. It is derived from Kaggle: https://www.kaggle.com/c/tabular-playground-series-jul-2021/data. 
There are 7111 records in the dataset. The data is cleaned and split into a training set (60%) ,a validation set(20%),
a testing set (20%). There are a total of twelve features in the dataset. 

------------------------------------------

# Dataset Format

The dataset must be in a CSV file formatted exactly as the
values in the tables below.  
1.	Date - Date and time of the record measurement.
2.	Deg_C - Temperature in Celcius.
3.	Relative Humidity - Relative humidity is the percentage of the current absolute humidity to the highest possible absolute humidity.
4.	Absolute Humidity - Absolute humidity is the mass of water vapor divided by the mass of dry air in a volume of air at a given temperature.
5.	Sensor_1 - (tin oxide) hourly averaged sensor response (nominally CO targeted)
6.	Sensor_2 - (titania) hourly averaged sensor response (nominally NMHC targeted)
7.	Sensor_3 - (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
8.	Sensor_4 - (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
9.	Sensor_5 - (indium oxide) hourly averaged sensor response (nominally O3 targeted)
10.	Target_Carbon_Monooxide - Amount of Carbon Monoxide in air, which we need to predict. 
11.	Target_Benzene - Amount of Benzene in air, which we need to predict.
12.	Target_nitrogen_oxide - Amount of Nitrogen Oxide in air, which we need to predict.





| Date    | Deg_C   | Relative Humidity | Absolute Humidity|Sensor_1|Sensor_2|Sensor_3|Sensor_4|Sensor_5|Target_Carbon_Monooxide|Target_Benzene|Target_nitrogen_oxide|
|---------|---------|-------------------|------------------|--------|--------|--------|--------|--------|-----------------------|--------------|---------------------|



------------------------------------------

# Evaluation

Continuous forecasts are evaluated with sklearn regression metrics models for Linear Regression, 
Polynomial Regression, Random Forest and Neural Networks are saved respectively. Thus, the models can be used to predict on the test data saving the time to train the entire dataset for each model.  
The RMSLE will be the primary scoring metric for pollution predictions.
Other metrics used are: MAE, MAPE, RMSE, R-squared.

------------------------------------------

### Note:
- This project was created for DS5220 Supervised Machine Learning

------------------------------------------

##### Made with :heart: by [@rohiiit](https://github.com/rohiiit), [@Rajdoshi99](https://github.com/Rajdoshi99) and [@Tushita-Gupta](https://github.com/Tushita-Gupta)
