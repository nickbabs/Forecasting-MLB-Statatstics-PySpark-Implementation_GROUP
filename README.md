## Forecasting-MLB-Stats-Machine-Learning-PySpark-implementation
This is a collaborative implementation of the MLB-Season-Ending-Statistics-Predictors project using PySpark and the inclusion of a conference-style paper. 
The game of baseball is heavily driven by statistics, and with the advent of technology, teams are using analytics to make decisions regarding players 
and game strategies. 
## Modeling
This project aims to predict a player's final season-ending statistics for certain categories using Linear Regression and XGBoost 
prediction models.
## Process
The prediction process involves predicting the amount of HR per player in the 2016 season, followed by the amount of HR per player in 2017. The data 
from these two seasons is combined to predict the amount of HR per player in 2018, and this process is repeated for 2019 and 2021. The same process is 
followed for other features such as OBP, RBI, and AVG.

To use this project, clone the repository and run the Jupyter notebook containing the code. Note that PySpark will need to be installed beforehand.
The notebook contains step-by-step instructions for pre-processing the data and making predictions using the two models. The conference-style paper 
provides an in-depth analysis of the project's process, methodology, and results.
