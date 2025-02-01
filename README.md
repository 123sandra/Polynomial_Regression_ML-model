# Polynomial_Regression_ML-model
Created a dataset with Temperature and it's corresponding pressure and compared predictio accuracy of the model by using both Linear Regression and Polynomail Regression. And also loaded a dataset of position level and their corresponding salary. <br>
1. Created a dataframe with __temperature(i/p) and pressure(o/p)__ , then splited the dataset into X and y.
2. Imported Linear Regression, trained the model and predicted.
3. Plotting with the help of Matplotlib library the actual and predicted values and also finding the **Best Fit Line**.
4. Finding the performance measure of the model and found out that the model's performance is bad the predictions are not accurate as there is a huge difference between predicted and atcual values.
5. Approximate R2 Score is **70%** using Linear Regression.
6. Now let's do Polynomial Regression for that import __PolynomailFeatures__ from sklearn library.
7. Training and predicting the model.
8. Plotting to see the visual representation of Actual and Predicted values.
9. Finding the performance measure of the newly created model and the model's performance is much better and more accurate and there is very less difference between predicted and actual value.
10. Predicting with new value
11. Repeated all the task with newly added dataset for predicting the Salary based of position levels.
# Conclusion
while assigning degree of polynomial i firstly assigned 3 but the prediction was not accurate and the R2 Score was low thus i changed to 5 there by i could increase my R2 score and there is very minute difference between actual and predicted values. <br>
New R2 Score is __99.9%__.
