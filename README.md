# GE-data-mining-contest
Predicting countries' power consuption for GE data mining contest at Hack GSU! Sadly my submission came ten minutes late :(
---------------------------------------------------------------------------------------------------------------------------
The program takes economic data from 14 different countries along with their power output per capita in kwh. From this training data it attempts to predict the power output for two previously unobserved countries.
To this end, two models are trained. A classifier, implemented by a support vector machine, which attempts to determine which countries these new countries most resemble economically, and a regressor, implemented by an SVR. 
Once the classifier determines which training country the new country most resembles, the regression model is fit to the data of that training country, and the new country's data is run through that model to produce a prediction.
