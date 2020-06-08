# Energy Price Modelling

Full project available as a PDF:
https://github.com/RMCox/Energy-Price-Prediction/blob/master/Energy_Price_Prediction.pdf

Time Series Analysis in R. Used Generalised Additive Models (GAMs) to predict energy prices on the energy futures markeet, and choose an optimal strategy to minimise costs for an energy supplier.

* Performed EDA to explore the variable distributions and relationships, which revealed the need for a non-linear model.
* Feature engineering to add lagged variables, which increased the variance explained by the GAMs
* Tested the effectiveness fof ARIMA modelling
* Performed bootstrap aggregation to guage how the model would perform on many random points in the data. Constructed confidence intervals for energy costs.



