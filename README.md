# Kaggle Houseprice Prediction
My codes in Kaggle houseprice prediction competition


## Competition description 

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## Evaluation
### Goal

It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

### Metric

Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the **logarithm** of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

### Submission File Format

The file should contain a header and have the following format:

Id,SalePrice

1461,169000.1

1462,187724.1233

1463,175221

etc.

You can download an example submission file **(sample_submission.csv)** on the Data page.


## Achivement & Ranking
• Engineered features and developed machine learning models to predict house prices using the Kaggle dataset comprising 79 attributes of homes in Ames, Iowa

• Preprocessed data employing techniques like normalization and missing value imputation to enhance model accuracy

• Experimented with various regression models, including Ridge regression, XGBoost and Random Forest, optimizing for the lowest Root Mean Square Error (RMSE)

• Utilized cross-validation and grid search for hyperparameter tuning to prevent overfitting and ensure generalization of the model

• Created a comprehensive Jupyter Notebook documentation, illustrating exploratory data analysis, model development, and validation process

Models I used: 

    * Lasso Regression
    * Ridge Regression
    * Elastic-net Regression
    * Decision tree
    * Random forest
    * XGBoost regressor

Attain 0.13312 rmse, with ranking Top 30%
