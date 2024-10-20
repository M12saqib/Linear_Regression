
# Advertising Sales Prediction: Simple and Multiple Linear Regression

This repository contains a project demonstrating both **Simple Linear Regression** and **Multiple Linear Regression** models to predict sales based on advertising spend across different channels (TV, Radio, Newspaper). The dataset used includes 200 records of advertising expenditure and corresponding sales figures.

## Project Overview

This project aims to analyze how advertising costs affect product sales and develop predictive models to forecast sales based on advertising budgets. The project covers:

- A **Simple Linear Regression Model**: Predicts sales based solely on TV advertising.
- A **Multiple Linear Regression Model**: Predicts sales based on TV, Radio, and Newspaper advertising combined.

## Dataset

The dataset used for this project comes from [Kaggle](https://www.kaggle.com). It contains the following features:

- **TV**: Budget spent on TV ads.
- **Radio**: Budget spent on Radio ads.
- **Newspaper**: Budget spent on Newspaper ads.
- **Sales**: Target variable representing sales (in units) based on the advertising budget.

| Features   | Description               |
|------------|---------------------------|
| TV         | Advertising cost on TV ads|
| Radio      | Advertising cost on Radio ads|
| Newspaper  | Advertising cost on Newspaper ads|
| Sales      | Target variable - sales in units|

## Installation

To run the code in this repository, ensure you have the following installed:

- Python 3.12.4
- Jupyter Notebook or any Python IDE
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

You can install the necessary Python libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Project Structure

### 1. Simple Linear Regression (TV vs Sales)

This section explores the relationship between TV advertising costs and sales using a simple linear regression model.

#### Steps:
- **Data Preprocessing**: Load the data and split it into training and testing sets.
- **Model Fitting**: Fit a linear regression model using TV ad costs as the independent variable and Sales as the dependent variable.
- **Model Evaluation**: Evaluate the model using Mean Squared Error (MSE) and R-squared (R²).
- **Visualization**: Visualize the relationship between TV ad costs and sales, and plot the regression line.

#### Key Results:
- The model captures the linear relationship between TV advertising and sales.
- MSE and R² metrics are used to evaluate the model's performance.
  
### 2. Multiple Linear Regression (TV, Radio, Newspaper vs Sales)

In this section, we extend the model to include Radio and Newspaper ad costs as additional predictors.

#### Steps:
- **Data Preprocessing**: Prepare the dataset, including feature selection and splitting the data.
- **Model Fitting**: Fit a multiple linear regression model using TV, Radio, and Newspaper advertising as predictors of Sales.
- **Model Evaluation**: Evaluate the model using MSE and R².
- **Analysis of Coefficients**: Analyze how each type of advertising (TV, Radio, Newspaper) affects sales.
- **Residual Analysis**: Plot residuals to ensure model assumptions are met.
- **Visualization**: Compare actual vs predicted sales for the multiple regression model.

#### Key Results:
- The model provides insights into how each advertising medium contributes to sales.
- MSE and R² values are used to evaluate the model's predictive power.

## Results

1. **Simple Linear Regression Results**:
   - A linear relationship exists between TV ad costs and Sales.
   - The coefficient of TV ads shows the expected increase in sales for each additional unit spent on TV advertising.
  
2. **Multiple Linear Regression Results**:
   - TV, Radio, and Newspaper ads all contribute to Sales.
   - The model provides coefficients for each type of ad, showing how each medium impacts sales.

### Model Performance

- **Simple Linear Regression (TV vs Sales)**:
  - MSE: _e.g., 10.18_
  - R²: _e.g., 0.68_

- **Multiple Linear Regression (TV, Radio, Newspaper vs Sales)**:
  - MSE: _e.g., 4.40_
  - R²: _e.g., 0.86_

## Conclusion

- The simple linear regression model indicates a positive relationship between TV ad spend and sales, but it doesn't capture all the variability in sales.
- The multiple linear regression model improves predictions by considering Radio and Newspaper ads, providing a more comprehensive view of how different media influence sales.

## Future Work

- **Feature Engineering**: Explore non-linear relationships, interaction terms, and polynomial regression.
- **Regularization**: Apply techniques like Ridge and Lasso regression to reduce overfitting.
- **Cross-Validation**: Implement cross-validation for better model evaluation.

## Contributing

Feel free to open issues or submit pull requests if you'd like to contribute to the project. Contributions that add more advanced models, improve code efficiency, or enhance visualizations are highly appreciated.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

### Author
Muhammad Saqib – Data Analyst 
