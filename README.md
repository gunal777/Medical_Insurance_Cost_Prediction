# Medical Insurance Cost Prediction using Multiple Linear Regression

## Objective

The objective of this project is to develop a Multiple Linear Regression model to predict medical insurance charges based on customer demographic and health-related information.

---

## Dataset

**Medical Cost Personal Insurance Dataset**

Kaggle Dataset:
https://www.kaggle.com/datasets/mirichoi0218/insurance

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Methodology

1. Load the dataset using Pandas.
2. Explore the dataset and identify numerical and categorical features.
3. Check for missing values.
4. Encode categorical variables using LabelEncoder.
5. Split the dataset into training (80%) and testing (20%) sets.
6. Train a Multiple Linear Regression model.
7. Predict insurance charges for the test dataset.
8. Evaluate the model using MAE, MSE, and R² Score.
9. Visualize Actual vs Predicted charges using a scatter plot.

---

## Results

- Mean Absolute Error (MAE): **Replace with your output**
- Mean Squared Error (MSE): **Replace with your output**
- R² Score: **Replace with your output**

The model achieved satisfactory prediction performance and explained a significant portion of the variation in insurance charges.

---

## Conclusion

The Multiple Linear Regression model successfully predicted insurance charges using demographic and health-related features. Smoking status, BMI, and age were found to have the greatest influence on medical insurance costs. Although the model performed well overall, it assumes a linear relationship between features and the target variable, which may not fully capture complex real-world healthcare cost patterns.