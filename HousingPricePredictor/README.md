# Housing Price Predictor
## Background
Housing price prediction is one of the most famous tasks in ML/AL in the real-estate world. In this section, we will use housing price prediction to go over the basic ML models (linear and non-linear models).
## Course Content
This chapter involves four sections.
### 1. [Data Exploration](https://github.com/brookefzy/pitaya/blob/main/HousingPricePredictor/01_exploratory_data_analysis.ipynb)
* Use python data visualization package to conduct basic EDA (Exploratory data analysis)
* Understand data type
* Understand data distribution
* Analyze and impute missing values

### 2. [Linear models](https://github.com/brookefzy/pitaya/blob/main/HousingPricePredictor/02_linear_models.ipynb)
* Understand the differences between Ordinary Least Square Linear Regressions, Lasso Regressions, Ridge Regressions
* Understand overfit, bias, variance, and regularization
* Perform data split
* Use cross-validation to find the best alpha for a Lasso Regression
* Understand model evaluation metrics: R2, MSE, RMSE
* **Self-guide**: the student needs to finish the [homework](https://github.com/brookefzy/pitaya/blob/main/HousingPricePredictor/02b_advanced_feature_engineering.ipynb) for the first day.

### 3. [Non-linear models](https://github.com/brookefzy/pitaya/blob/main/HousingPricePredictor/03_nonlinear_models.ipynb)
* Use common non-linear regression models (Random Forest, Gradient Boosting Regressor, XGBoost) to predict housing price
* Hyperparameter tuning
* Compare evaluation metrics to evaluate all models
* Learn to use permutation importance to analyze feature importance for individual feature
* Understand SHAPLEY Values, partial dependence plot
* **Self-guide**: the student should use a different non-linear model and get the result for the test dataset provided by the exercise.

### 4. Case presentation
* Using the nonlinear model to estimate bus risk factors

## Reading list
### MUST READ:
```
@article{athey2019machine,
  title={Machine learning methods that economists should know about},
  author={Athey, Susan and Imbens, Guido W},
  journal={Annual Review of Economics},
  volume={11},
  pages={685--725},
  year={2019},
  publisher={Annual Reviews}
}
@article{chen2023algorithms,
  title={Algorithms to estimate Shapley value feature attributions},
  author={Chen, Hugh and Covert, Ian C and Lundberg, Scott M and Lee, Su-In},
  journal={Nature Machine Intelligence},
  pages={1--12},
  year={2023},
  publisher={Nature Publishing Group UK London}
}
```

