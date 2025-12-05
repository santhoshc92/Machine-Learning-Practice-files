**Bike Sharing Demand Prediction**

This project builds predictive models using Decision Tree Regressor and Random Forest Regressor to estimate the number of bikes rented per hour (cnt).
Project Objective

**The goals of this project are:**

Understand and analyze how weather and seasonal conditions impact bike rentals

Clean and preprocess the dataset

Explore and visualize data distributions (histograms, boxplots)

Train predictive models using Decision Tree and Random Forest

Perform hyperparameter tuning to reduce overfitting

Evaluate model accuracy using regression metrics (R², RMSE)

Provide business recommendations based on insights

**Dataset Description*

| Feature        | Description                                                                                                                           |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| **instant**    | Record index                                                                                                                          |
| **dteday**     | Date                                                                                                                                  |
| **season**     | Season (1: spring, 2: summer, 3: fall, 4: winter)                                                                                     |
| **yr**         | Year (0: 2011, 1: 2012)                                                                                                               |
| **mnth**       | Month (1 to 12)                                                                                                                       |
| **hr**         | Hour of the day (0 to 23)                                                                                                             |
| **holiday**    | Is the day a holiday?                                                                                                                 |
| **weekday**    | Day of the week                                                                                                                       |
| **workingday** | Is it a working day (not weekend or holiday)?                                                                                         |
| **weathersit** | Weather situation: <br> 1: Clear/Cloudy <br> 2: Mist + Cloudy <br> 3: Light Snow or Light Rain <br> 4: Heavy Rain, Thunderstorm, Snow |
| **temp**       | Normalized temperature (temp/41)                                                                                                      |
| **atemp**      | Normalized “feels like” temperature (atemp/50)                                                                                        |
| **hum**        | Normalized humidity (hum/100)                                                                                                         |
| **windspeed**  | Normalized wind speed (windspeed/67)                                                                                                  |
| **casual**     | Count of casual users                                                                                                                 |
| **registered** | Count of registered users                                                                                                             |
| **cnt**        | Total bike rentals (casual + registered)                                                                                              |

**Models Used**

Decision Tree Regressor

Random Forest Regressor

**Evaluation Metrics**

R² Score (Coefficient of determination)

RMSE (Root Mean Squared Error)

**Technologies Used**

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn (DecisionTreeRegressor, RandomForestRegressor)

Jupyter Notebook
