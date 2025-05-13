# House Price Prediction (California Housing Dataset)

This project demonstrates a beginner-friendly machine learning pipeline to **predict house prices** using the **California Housing dataset**. It includes data preprocessing, training a linear regression model, evaluating performance, and visualizing the results.

---

## Features

- Linear Regression using `scikit-learn`
- Model evaluation with **Mean Squared Error (MSE)** and **R² Score**
- Data visualizations:
  - Feature distributions
  - Correlation heatmap
  - Actual vs Predicted price scatter plot

---

## Dataset

We use the [California Housing dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html) which is built into `scikit-learn`.

Features include:
- Median Income
- House Age
- Average Rooms, Bedrooms
- Population
- Latitude & Longitude
- Median House Value (target)

---

## Installation

Make sure you have Python installed. Then install the required libraries:

```bash
pip install scikit-learn pandas matplotlib seaborn
```
## Visualizations

1. **Feature Distributions**  
   Helps understand the shape and spread of each input variable.

2. **Correlation Heatmap**  
   Displays correlations between all features and the target price.

3. **Actual vs Predicted Prices**  
   A scatter plot comparing true values with model predictions.

---

## Evaluation Metrics

- **Mean Squared Error (MSE):**  
  Measures average squared difference between actual and predicted values.

- **R² Score:**  
  Indicates how well the model explains the variability in the target. Ranges from 0 to 1.

---

## Future Improvements

- Try different models like **Random Forest**, **XGBoost**  
- Add **feature scaling** or **polynomial features**  
- Use **GridSearchCV** for hyperparameter tuning  
- Build a **web app using Flask or Streamlit**

---

## License

This project is open-source and free to use under the **MIT License**.

---

## Acknowledgements

- [Scikit-learn](https://scikit-learn.org/)  
- [Seaborn](https://seaborn.pydata.org/)  
- [California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
