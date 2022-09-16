# Overview

In this project for my Machine Learning class, I collaborated with one other person to predict the sales prices of used cars given attributes such as make, model, engine specifications, mileage, fuel economy, etc. The biggest challenge of this project was imputing missing data. We used a multi-step approach when filling out all the missing data. First, we grouped the data by make and model and used the values from existing entries to fill in the missing entries. Then we grouped by other relevant variables to fill out the remaining blanks. For example, we grouped all compact cars together and took the median engine displacement to fill out the missing values in displacement.

After cleaning the data, we used the XGBoost algorithm to predict prices. We used RMSE as a metric for measuring model accuracy.
