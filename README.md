# House-Price-Prediction-from-Living-Area-Simple-Linear-Regression-
Predicting house sale prices in Ames, Iowa from living area using simple linear regression in Python.
House Price Prediction from Living Area (Simple Linear Regression)

Predicting the sale price of houses in Ames, Iowa from their above-ground living area, using a simple linear regression model built end to end in Python: data understanding, cleaning, exploratory analysis, modeling, evaluation, and recommendations.

Overview

Living area is one of the first things buyers and agents look at when pricing a house. This project asks a focused question: how much of a house's sale price can be explained by its living area alone, and how accurately can we predict price from it?

I use a simple linear regression (one feature, one target) to quantify the relationship, measure how well it predicts unseen houses, and examine where it works and where it falls short.

Objective
Build a simple linear regression model: SalePrice = b0 + b1 × Gr Liv Area
Quantify the price change associated with each additional square foot
Evaluate the model honestly on unseen data and compare it against a naive baseline
Document the data issues found along the way (outliers, skewness) and how they were handled
Dataset
Source: Ames Housing dataset (De Cock, 2011), downloaded from Kaggle
Size: 2,930 house sales and 82 columns, covering sales in Ames, Iowa between 2006 and 2010
Variables used in this project:
Role	Column	Description
Target (y)	SalePrice	Sale price in US dollars
Feature (X)	Gr Liv Area	Above-ground living area in square feet

The remaining columns describe lot, building, basement, garage, and sale characteristics. They are explored for context but not used in the model, since the goal is a simple (single-feature) regression.

Methodology
Understand the data: shape, data types, missing values, column meanings
Define the problem: regression task, target, feature, and success metrics
Clean the data: duplicates, invalid values, and outlier investigation
Exploratory data analysis: distributions, relationship between area and price, linearity check
Split the data: train and test sets, to evaluate on houses the model has not seen
Baseline: a naive model that always predicts the average price
Build the model: fit the simple linear regression on the training set
Evaluate: R², RMSE, and MAE on the test set, plus residual analysis to check the model assumptions
Interpret: what the slope and intercept mean in dollars
Recommendations: what the model can and cannot be used for, and next steps
Tools

Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

Results

To be completed once the model is built. Replace the placeholders below with the actual numbers.

Metric	Baseline (mean price)	Simple linear regression
R² (test)	[ ]	[ ]
RMSE (test)	[ ]	[ ]
MAE (test)	[ ]	[ ]

Model equation: SalePrice = [ ] + [ ] × Gr Liv Area

Key Insights

To be completed after the analysis.

[Relationship between living area and price, and its strength]
[Effect of outliers or very large houses on the model]
[Residual behavior: is the error constant across small and large houses?]
[Whether the price distribution needed a transformation]
Recommendations

To be completed after the analysis.

[What the model is suitable for, and its limits]
[Next steps, for example adding other features such as overall quality, neighborhood, or year built]
