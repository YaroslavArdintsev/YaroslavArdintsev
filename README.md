# Hello, my name's Yaroslav! 👋

Junior ML Engineer who turns raw data into working predictive models. My projects cover the full modeling cycle: 
data cleaning and analysis, feature engineering, training, validation, and interpretation of results. 
The next step is to deploy models to production and master MLOps.

### Tech stack

- **Languages:** Python, SQL, R
- **ML:** scikit-learn, CatBoost, LightGBM, XGBoost, PyTorch, BART
- **Data:** pandas, numpy, scipy, matplotlib, seaborn, tidyverse, ggplot2, data.table, rsample
- **Databases:** PostgreSQL, MySQL, SQLite, SQLAlchemy
- **Engineering:** Git, Docker, pytest

### Featured projects

#### Hackathon “Intelligent Data Analysis in the Oil and Gas Industry”

Mineral classification from scanning electron microscopy (SEM) images

`pandas` · `numpy` · `scikit-learn` · `catboost` · `mendeleev`

* built an end-to-end machine learning pipeline for mineral classification from scanning electron microscopy (SEM) data
* cleaned the dataset by removing invalid outliers—cases where elemental concentrations exceeded 100%—and corrected mineral labels in the target variable
* leveraged additional mineralogy study to engineer new high-signal features, primarily ratios of elemental fractions across minerals
* developed and benchmarked several models, including Random Forest, SVM, and CatBoost, selecting Random Forest as the best-performing solution
* optimized hyperparameters using GridSearchCV and StratifiedKFold
* achieved 0.81 accuracy and 0.63 F1-score in cross-validation

[View project →](https://github.com/YaroslavArdintsev/Intelligent-Data-Analysis-in-the-Oil-and-Gas-Industry)

#### "AI Challenge — International AI Competition for Children and Youth", Qualification Stage

A solution for a user-retention prediction task focused on forecasting whether a user would return to the app

`rsample` · `BART` · `ROCR`

* applied logarithmic transformations to selected features to smooth heavy-tailed distributions and engineered a set of new high-signal features
* used the ROCR library to identify the optimal classification cutoff
* trained a Bayesian Additive Regression Trees (BART, i.e., Bayesian sum-of-trees) model to predict the target variable
* achieved a ROC-AUC of 0.65 on the leaderboard

[View project →](https://github.com/YaroslavArdintsev/AI-Challenge-Qualification)

#### Course Project: Customer Churn Prediction for a Telecom Provider — “Machine Learning in Python”

An end-to-end machine learning project focused on predicting customer churn for a telecom service provider

`numpy` · `pandas` · `matplotlib` · `seaborn` · `scikit-learn`

* performed exploratory data analysis and preprocessing: examined feature distributions, handled missing values, encoded categorical variables, and prepared the dataset for modeling
* trained and benchmarked three tree-based algorithms—Decision Tree, Random Forest, and AdaBoost—to compare their ability to identify customers at risk of churn
* evaluated model performance using cross-validation to ensure stable and generalizable results
* achieved 0.84 accuracy on cross-validation with the best-performing model

[View project →](https://github.com/YaroslavArdintsev/ML-Python-Project)

### Contact

Telegram: [@CarleMagne](https://t.me/CarleMagne)
Email: [jaricardintsev@gmail.com](mailto:jaricardintsev@gmail.com)
