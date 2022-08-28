# Medical-Cost-Analysis-Project

A Machine Learning project trained by "Medical Cost Personal Datasets" from Kaggle and performance of different Regression models are compared.

In this project Medical Cost Personal Datasets from Kaggle is used.

The dataset includes 1338 rows x 7 columns. The columns are the features related to each person.

Features in the Medical Cost Personal Dataset:

Age: The age of the person
Sex: The gender of the person
BMI: The body mass index of the person
Children: Number of children a person has
Smoker: Smoking status of the person
Region: The region where the person lives
Charges: The amount of the person's medical insurance fee.
The main purpose of the Medical Cost Analysis Project is to analyze the Medical Cost Personal Dataset and predict the medical cost of people by their age, sex, BMI, children, smoker and region data.

To analyze the dataset, Medical Cost Personal Dataset is cleaned from outliers, and correlation of different features are examined.

Then, the categorical features in the dataset are converted into a new binary feature for each category, and a value of 1 is assigned to the feature of each sample that corresponds to its original category using the One-Hot encoding method.

The correlation of different features is examined through data visualization technics visualize their relationship.

After cleaning the dataset and preprocessing the dataset, five different regression models are initialized.

The regression models used in the Medical Cost Analysis Project:

Linear Regression
Decision Tree
Random Forest
Gradient Boosting
Ada Boost Regressor
Several regression models were selected and trained on the preprocessed data.

The performances of the chosen models were examined using cross-validation.

The best performing model is selected

Hyper-parameters are optimized

By the Grid Search method, parameters are optimized

The optimized model was evaluated using the regression model evaluation metrics. (e.g., Mean Squared Error, Mean Absolute Error, etc.)
