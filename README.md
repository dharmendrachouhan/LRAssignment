# Bike sharing 
> Customer want to understand the factors affecting the demand for shared bikes in the American market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information

Customer want to understand the factors affecting the demand for shared bikes in the American market.The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demand

The project contain a jupiter notebook which reads a csv file which contains data of shared bike use and based on that creates a linear model to find the variables that impact the demand of bikes.


## Conclusions

Summary of the above model
- The model has R2 of .78 which is decent
- The model has Adjusted r2 also similar to R2 so there is no extra variable
- The value of R2 for test data is 0.71 which is close to value of test data. So the model is not overfit.
- The Error terms are randomly distributed
- But the plot of Actual v/s Predicted is not a prefect fit
- In the above model does not include month it relies on season and other variables but the month wise graph shows that month has significant impact. Lets do the analysis by converting month as a dummy variable

Which variables are significant in predicting the demand for shared bikes.
- The rental seems to be increasing with year. So we can expect next year to have more demant for bike rental. This seems to be because the covid situation is improving.
- A working day has positive impact on rental which means our users might be people using the bike to go to office.
- On a day with high windspeed, snow and rain, cloudy  the rental is impacted negatively. Users might be using cars or public conveyance on such days.
- The months of Dec, Feb, Jan and Mar have negative impact on rental.
- The month of Sep has a positive impact on rental.
- Sat has a positive impact on rental.

## Technologies Used
- seaborn -Version: 0.13.2
- numpy - version 1.26.4
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- scikit-learn - version 1.2.2
- statsmodels - version 0.14.0


## Contact
Created by [@githubusername] - feel free to contact me!
