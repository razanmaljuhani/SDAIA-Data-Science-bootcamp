# Predection the price of a car. 
This is Project of the T5 - Data Science Bootcamp (Tuwaiq) provided by SDAIA.
(Razan Aljuhani)
# Abstract
The project aims to establish effective models for predicting the price of a used car depending on its features and attributes by using Linear regression model. So, the companies can make professional strategies of business to meet a particular level of car selling price.
# Design
# Data
Vehicle dataset that consists of data about the used cars listed on this Indian website www.cardekho.com. The third version of dataset was updated in 2020 and contain 8111 data points and 13 attributes. 
# Algorithms
Frist, the Car_details databace was splitted into (training set) for modelling process and (test set) for evaluation process.

### Algorithm
Feature Engineering was applied on the dataset for improving machine learning model performance and accuracy.
- Compute the 'Car_Age' by engineer the data through deducting the 'year' column from 2021 will give the age of car.  
- Establish the 'Car_Brand' by splitting the 'Car_Name' column.
- 
##### The used models
Lineaer Regression, Random Forest Regressor and XGBoost Regression.

The Scores of Accuracy of the models:
- The accuracy of Lineaer Regression(Ordinary Least Square), Lineaer Regression(Ridge) and Lineaer Regression(Lasso) approxemitly = 86% (Train set) and 85% (Test set).
- The accuracy of  Random Forest Regressor = 98% (Train set) and 91% (Test set).
- The accuracy of  XGBoost Regression = 99% (Train set) and 90% (Test set) l 

#### Model Evaluation
The modes was evaluation using the following main metrics for model evaluation in regression:
- Mean Absolute Error      :  16%
- Mean Squared  Error      :  5%
- Root Mean Squared  Error :  22%
- R Squared Error          :  90% 

The accuracy of all used models was good. However, the best model is XGBoost regression because its highest and greate accuracy with score(99%) which mean it generalize better than other models. Also, Linear model is a great model choice since its computational inexpensive. The result of accuracy inducates that the model is generalized and no overfitting. 

# Tools
•	**Environment**: Jupyter Notebook. 
•	**Programming** Language: Python.
•	**Data processing**: Pandas, NumPy.
•	**Visualization**: Seaborn, Matplotlib.
•	**Modeling**: Scikit-learn.

# Communication


