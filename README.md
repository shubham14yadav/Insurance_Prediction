# Insurance_Prediction

Description:

In the "Healthcare Charges Prediction Project," I developed a machine learning model to predict medical charges for individuals based on various factors. Using Python and the scikit-learn library, I built a simple linear regression model to analyze a dataset containing information such as age, sex, body mass index (BMI), number of children, smoking habits, and region. To handle categorical features, I applied appropriate encoding techniques.

By splitting the dataset into training and testing sets, I trained the model on a portion of the data and evaluated its performance on unseen data. The model's predictive capabilities were assessed by calculating the charges for the test set and comparing the predicted values with the actual charges.

Comparing the performance of the Random Forest Regressor and Linear Regression models on the given dataset:

Random Forest Regressor:

Mean Squared Error (MSE): 22042681.15
R-squared (R2): 0.8580
Linear Regression:

Mean Squared Error (MSE): 33979257.05
R-squared (R2): 0.7811
Based on the evaluation metrics:

The Random Forest Regressor outperforms the Linear Regression model in terms of both MSE and R-squared.
The lower MSE value of the Random Forest Regressor indicates that it provides more accurate predictions compared to the Linear Regression model.
The higher R-squared value of the Random Forest Regressor (0.8580) suggests that it explains a larger portion of the variance in the target variable than the Linear Regression model (0.7811).

Therefore, the Random Forest Regressor is a better choice for predicting medical charges using the given features.
