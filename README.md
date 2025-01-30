Machine Learning Project on Predicting the Car Price.
Problem Description:
A Chinese automobile company aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to 
their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. 
Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. 
Essentially, the company wants to know:
•	Which variables are significant in predicting the price of a car
•	How well those variables describe the price of a car
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.

Business Goal:
We have to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables.
They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for the management to
understand the pricing dynamics of a new market.
Dataset:  https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view
Loaded the dataset and performed necessary preprocessing steps like Acquire the dataset,Importing all necessary libraries,importing the dataset,Finding missing values,
Finding and handling outliers,(visualizing that using plots),Encoding categorical data,Feature selection,Splitting the dataset,and Feature scaling.
Implemented the following five regression algorithms:
1) Linear Regression
2) Decision Tree Regressor
3) Random Forest Regressor
4) Gradient Boosting Regressor
5) Support Vector Regressor
•	Compared the performance of all the models based on R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
•	Identified the best performing model as theRandom Forest Regressor.
•	Performed hyperparameter tuning and checked whether the performance of the model has increased.
 •	Identified the significant variables affecting car prices (feature selection)  
Toyota is the most preferred car company.Price of the car is highly (positively) correlated with wheelbase, carlength, carwidth, curbweight, enginesize, horsepower.
The cars having high mileage may fall in the 'economy' cars category, and are priced lower.



