# housing_price_analysis
Here we use XGBoost to train the model and Predict the price based on the parameters available
1. We Load the CSV file and create a dataframe
2. Then we do the cleaning by checking if there are any missing values in our data.
3. Using KNN we replace the null values to the mean of the nearest 3 values.
4. We do one hot encoding to replace the object type values into boolean values using get_dummies
5. Then we check the values on each column using histogram
6. We check for correlation in between the parameters in the data using heatmap from seaborn
7. Then we will check for the closest related vales and replace them with the calculated fields
8. Using train_test_split from sklearn we split data, here we split the data into 80% - train and 20% - test data
9. we create a model with XGBRegressor.
10. Following it, we use the model to predict the x_test and evaluate the data with the y_test.
