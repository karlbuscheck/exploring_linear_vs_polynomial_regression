# Exploring Overfitting with Linear and Polynomial Regression Models

## Project Overview

In this notebook, we'll work with a housing dataset to explore how different types of regression -- including both **linear** and **polynomial** -- impact model fit, performance, and the risk of **overfitting**. Along the way, we'll dig into Scikit-learn's **Pipeline** and **GridSearchCV**, and learn all about the trade-off between model complexity and accuracy. As we'll see, complexity doens't *always* lead to power -- sometimes, it introduces **noise, variance, and *chaos***.

Here's the path we'll follow:

## The Pipeline:

- Load and explore the dataset
- Set X and y, the feature and target
- Visualize the relationship between feature and target variables
- Import and fit the model
- View model parameters and performance
- Predict the price for a given house
- Visualize the regression line
- Evaluate model performance with error metrics
- Add polynomial features to the model
- View the polynomial model's learned parameters and performance
- Build a pipeline
- Visualize the new, polynomial regression line
- Re-run the model with higher polynomial terms
- Find the best polynomial degree with Grid Search, plus takeaways and observations
- Use multiple features to build a linear regression model

## Tools & Libraries Used

- **Jupyter Notebook** — the interactive environment used to explore, build, and document the entire modeling process   
- **Python 3.12.7** — base language powering all modeling, iteration, and data prep   
- **scikit-learn** - for linear and polynomial regression, feature scaling, model pipelines, and hyperparameter tuning via GridSearchCV, and model evaluation
- **matplotlib** - for data visualization
- **pandas and numpy** - for data manipulation and analysis


## Acknowledgements

This notebook is built on top of a lecture by Tao Li, Associate Professor in the department of Information & Analytics at the Leavey School of Business at Santa Clara University. Thanks to the professor for designing lectures that inspire further exploration.
