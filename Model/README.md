# Weather Forecast Prediction
This project aims to build a weather prediction model that can forecast weather conditions based on historical weather data. The project focuses on predicting attributes such as temperature, precipitation, and other weather-related variables for future dates. To achieve this, various machine learning models are implemented and evaluated. The goal is to create an accurate and reliable weather prediction system that can be used for planning and decision-making in various applications.
## Models Used:
<br>
1.Linear Regression(Ridge Regression): A basic regression model that establishes a linear relationship between input features and the target variable. This model is suitable for continuous weather parameter predictions.<br>
2.Random Forest: Random Forest is an ensemble learning method based on decision trees. It is employed as a regressor in this project for weather prediction.<br>
3.K-Nearest Neighbors (KNN): KNN is a versatile model that can be used for both classification and regression tasks. In this project, it is used as a regressor for predicting weather parameters.

# Project Flow

1. **Data Collection:** Dataset taken from  [noaa](https://www.ncdc.noaa.gov/cdo-web/search)
2. **Data Preprocessing:**
   Clean the raw weather data, addressing missing values and outliers.<br>
   Create new features or transform existing ones to improve model performance.<br>
   Split the data into training and testing sets to train and evaluate the models.<br>
3. **Model Selection and Training:**
   Selected Linear Regression, K-Nearest Neighbors (KNN), and Random Forest as the candidate models and trained them.

4. **Model Evaluation:** 
  
  | Model | MAE | MSE |
  |----------|----------|----------|
  | Linear Regression |	4.787 |	37.515 |
  | Random Forest |	4.899	| 39.661 |
  | KNN Regressor	| 5.206	| 44.934 |

  Linear Regression has the lowest MAE, indicating that it has the best accuracy in predicting weather, on average, compared to the other two models. It also has     the lowest MSE, implying better overall performance.
  
  Random Forest has a slightly higher MAE and MSE than Linear Regression but is still a good model for weather prediction.
  
  KNN Regressor has the highest MAE and MSE among the three models, suggesting that it might not perform as well as the other models on this specific dataset.

5. **Model Comparison:**
  Based on the MAE and MSE values, Linear Regression is the best-performing model for your weather prediction, followed by Random Forest and KNN Regressor. These     metrics indicate the average prediction error and the squared error, respectively, where lower values are generally better.

6. **Visualisation:**   
   ![Plot Between Actual values and predicted values](Images/diffplot.jpg)

   

8. 
9. 



