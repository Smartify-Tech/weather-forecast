
# Simple Univariate Lineer Regression using scikit-learn:
Predicting Maximum temperature given the minimum temperature

This project attempts to apply my learning to build a simple linear regression.

The dataset used for this project is gotten from kaggle: [The dataset contains information on weather conditions recorded on each day at various weather stations around the world. Information includes precipitation, snowfall, temperatures, wind speed and whether the day included thunder storms or other poor weather conditions.](https://www.kaggle.com/datasets/smid80/weatherww2)

Firstly, simple approach was applied which was:
* cleaning the data
* selecting the target and feature variable
* fitting the model
    
Evaluating the model gave an RScore of **0.769** and a RMSE of _____

In attempt to improve the model performance, the dataset was:
* explored
* outliers was removed and
* the dataset was split into two categories
   * weather observations for zero precipitation
   * weather observations for precipitations greater than zero
* Finaly, fitting a linear model on the two categories
    
Evaluating the performances, the model for weather observations where precipitation is greater than zero performed better than the other (precipitation = 0) with an RScore of **0.88** and RMSE of **2.76**

## Note:
Note that a better model can be achieved by adding more predictor variables like Day of the year, month, and Precipitation value; but for the sake of learning I have limited this to one predictor variable and one response variable

## Technologies used:
A list of technologies used within the project:
* [scikit-learn](https://scikit-learn.org/)
* [pandas](https://pandas.pydata.org/)
* [numpy](https://example.com)
* [matplotlib](matplotlib.org)
