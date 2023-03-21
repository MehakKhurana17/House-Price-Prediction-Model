# House Price Prediction Model
I have made this House Price Prediction Model using Linear Regression.

![alt text]([http://url/to/img.png](https://th.bing.com/th/id/R.d5c5f2246919265f53e6f56f80071dd3?rik=Q7O1od8exJDnbQ&riu=http%3a%2f%2fcdn.wallpapersafari.com%2f37%2f82%2fBI78kU.jpg&ehk=yP98fVqkFdzsxnJdZ17FmIQKByMdglW%2bEUXxXB7Mf6o%3d&risl=&pid=ImgRaw&r=0))


 ## Linear regression 
 
 It is used when we want to make predictions for continuous variables (in our case it's house price). The independent variable (or target column) is predicted based on how the value of the dependent variable is changing according to the value of the independent variable.

## Objective:

A machine learning model is to be proposed to predict a house price based on data related to the house i.e., its area type, availability, location, size, society, total square ft, bath and balcony.

## Steps followed are:

 📌 Applied data preprocessing and preparation techniques in order to obtain clean data which includes following steps:

1. Importing and understanding of data
 
2. Checking for duplication 

3. Missing value check -> In case null values are present, simply drop the rows or use imputation techniques to fill those null values.

4. Correlation Check -> The performance of some algorithms can deteriorate if two or more variables are tightly related, called multicollinearity. An example is linear regression, where one of the offending correlated variables should be removed in order to improve the skill of the model.

5. Data Reduction -> Some columns or variables can be dropped if they do not add value to our analysis.

6. Data Cleaning/Wrangling -> Some data may have data entry errors, and some variables may need data type conversion.

7. Feature Engineering -> Feature engineering refers to the process of using domain knowledge to select and transform the most relevant variables from raw data when creating a predictive model. The main goal of Feature engineering is to create meaningful data from raw data.

8. Univariate Analysis -> Analyzing/visualizing the dataset by taking one variable at a time.

9. Bivariate Analysis -> Bivariate Analysis helps to understand how variables are related to each other and the relationship between dependent and independent variables present in the dataset.

📌 Built machine learning model to be able to predict house price based on house features using Linear regression, Lasso regression and Ridge regression which includes following steps:

1. Splitting data into training and testing data

2. Building and training the model

3. Making predictions from the model

4. Testing the performance of the model -> There are three main performance metrics used for regression machine learning models:
a. R square/Adjusted R square
b. Mean absolute error (MAE)
c. Mean squared error (MSE) / Root mean square error (RMSE)

## Model Evaluation

Linear regression and Ridge regression both performed well giving a training accuracy of around 80.6 % and testing accuracy of almost 81% along with R square values around 0.81.+
