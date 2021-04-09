# Automobile-Price-Prediction
Predict fuel consumption in MPG using Linear regression model.

Contents

This project is meant to explore, analyse, visualize and predict the predict is the fuel consumption in MPG:
 1.   cylinders    
 2.   displacement  
 3.   horsepower    
 4.   weight        
 5.   acceleration  
 6.   model year    
 7.   origin        
 8.   car name     
 9.   mpg          - Target variable

Machine Learning Steps Follwed to acheve the objective.
1. Import necessary Libraries
2. Read the csv dataset
3. Check for the null values and the unwanted values in the dataset
     - We checked for the null values and dropped '?' in horsepower column as there are only 6 columns for with the unwanted values.
4. Perform preprocessing and drop the column 'car name' as this column doesnot have any kind of impact on the  mpg of the car.    
5. Train Test Split the dataset.
6. Perform Linear Regression on Train data.
7. Use GridSearchCV cross validation method on the dataset and extract the best parameters on which the the datasets performance is best, based on accuracy score.
8. Use the best parameters - 'max_depth': 8, 'min_samples_split': 2 to prepare the model for prediction the traget variable.
9. Prediction of Train data
     - We got the score of  - 0.82815 and RMSE of 3.31591
10. Prediction of Test data 
     - We got the score of  - 0.79751 and RMSE of 3.28394

