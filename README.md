# 📝 Linear Regression Model for Is ill problem 📈

## 🔎 Overview
This code generates a sample dataset and uses it to build a linear regression model to predict whether a person is ill or not based on their age, weight, height, gender, and smoking status. The code also performs data preprocessing, including encoding categorical variables and splitting the data into training and testing sets. The performance of the model is evaluated using the mean squared error, and the results are visualized using scatter plots and bar graphs.

## 📦 Required Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🏃‍♀️ How to Run
1. Open the code file in a Python environment (e.g. Jupyter Notebook).
2. Run the code line by line, or run the entire code at once.

## 🛠️ Code Explanation
- The code first generates a sample dataset with 100 rows and six columns: age, weight, height, gender, smoking status, and illness status.
- The categorical variables (gender, smoking status, and illness status) are encoded using the LabelEncoder class from scikit-learn.
- The encoded columns are then used to create visualizations, including a histogram of age, a scatter plot of age vs. weight, and a box plot of smoking status vs. age.
- The data is then split into training and testing sets, and a linear regression model is created using the training data.
- The model is used to make predictions on the testing data, and the mean squared error is calculated to evaluate its performance.
- Finally, the predicted vs. actual values are plotted using a scatter plot, and the coefficients of the model are visualized using a bar graph.

## 👍 Conclusion
This code provides a basic example of how to build and evaluate a linear regression model for predicting illness status based on demographic and health-related variables. It can be used as a starting point for more complex regression models or for predicting other health-related outcomes based on different features.
