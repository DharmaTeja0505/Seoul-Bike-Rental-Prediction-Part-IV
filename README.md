# Seoul-Bike-Rental-Prediction-Part-IV

About the Data
The dataset consists of 14 features and 8760 records. T
information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation,
he dataset contains weather
Snowfall, Rainfall),
the number of bikes rented per hour and date information. We observe
collinearity between Temperature and Dew Point temperature and dropped Dew point
temperature , and observed Date is not much use to the classification problem and dropped
 the same and performed hot encoding on seasons and dropped 1 season feature in order to
 avoid collinearity .
 Project Outline
The Project is outlined to have 5 parts:
Part 1 : Run the clustering algorithms on your dataset and describe your observations (with plots) using K-Means and EM .
Part 2 : Apply the dimensionality reduction algorithms on your dataset and describe your observations(with plots) using Decision Trees, PCA, ICA and RCA.
Part 3: Run the clustering algorithms again, this time after applying dimensionality reduction. Describe the difference compared to previous experimentation (with plots).
Part 4: Run your neural network learner from assignment 3 on the data after dimensionality reduction (from task 2). Explain and plot your observations (error rates, etc.)
Part 5: Use the clustering results from task 1 as the new features and apply neural network learner on this new data consisting of only clustering results as features and class label as the output. Again, plot and explain your results
