# health-insurance-cross-sell-prediction

**Introduction**
> Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

**Problem Statements and Business Goal**
>1. Doing the Exploratory Data Analysis (EDA) to gain the customer insight.

> 2. Building the model(s) to predict whether a customer would be interested in vehicle insurance with providing data about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.


**Content Summary**

- 1) Understand and Hypothesis the problem

- 2) Exploratory Data Analysis : Trend, Trait and distribution across all features

- 3) insights : Cross-sell Target Customer Personas

     insights : Revealing Potential Channels and Areas for Engagement

- 4) Feature Engineering : Binning and Categorical Encoding

- 5) Feature selection with EDA insights and mutual_info_classif

- 6) Modeling and Evaluation

> Compare Baseline

> low-complexity models: Decision Tree.
> 
> ensemble methods: Random Forest
>
> boosting techniques: CatBoost for complex patterns.

vs the models with oversampling technique

> SMOTE vs ADASYN for oversampling

- 7) Hyperparameter Tuning

- 8) Evaluation Matrices

> : f1 score (Trade off rate of false negatives and false positives) and efficiency of handling imbalance issue

> : Also Recall (Concerning about false negatives)

- 9) Best model Prediction and Feature Importance

- 10) Conclusion and Recommendations for converting and raising customers interest
