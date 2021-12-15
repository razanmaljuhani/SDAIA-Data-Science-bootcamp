# Predection the price of a car.

Razan Aljuhani

# Abstract
The project aims to establish effective models for predicting the price of a used car depending on its features and attributes by using the Linear regression model. the database contains cars details of the Indian website www.cardekho.com. The project mainly goes through different steps including Data cleaning, EDA including visualization, Preprocessing followed by Modeling, and lastly evaluation of used models and determining the better model that achieve project goals. So, the companies can make professional strategies of business to meet a particular level of the car selling price.

# Design
**Problem statement**

Companies try to produce cars with special features to take attention in the market and compete with other competitors. They need to understand the dynamic changes of pricing in the market through the years, and the factors affecting the pricing of cars in the market. 

**Proposed solution**

The project will help in clarify the features has a direct impact on the target varible(Selling Price), by build an effective model using Linear regression.

# Data
Vehicle dataset that consists of data about the used cars listed on Indian website www.cardekho.com. The third version of the dataset was updated in 2020 and contains 8111 data points and 13 attributes. 

# Algorithms
First, the Car_details database was split into (training set) for the modeling process and (test set) for the evaluation process.

**Feature Engineering** was applied to the dataset for improving machine learning model performance and accuracy including the following:
- Compute the 'Car_Age'  by deducting the 'year' column from 2021 will give the age of the car.  
- Establish the 'Car_Brand' by splitting the 'Car_Name' column.

**The used models**
Linear Regression, Random Forest Regressor, and XGBoost Regression.

**The Scores of Accuracy of the models:**
- The accuracy of Linear Regression(Ordinary Least Square), Linear Regression(Ridge) and Linear Regression(Lasso) approximately = 86% (Train set) and 85% (Test set).
- The accuracy of  Random Forest Regressor = 98% (Train set) and 91% (Test set).
- The accuracy of  XGBoost Regression = 99% (Train set) and 90% (Test set).

**The evaluation of the models**
The modes were evaluated using the following main metrics for model evaluation in regression:
- Mean Absolute Error:  16%
- Mean Squared  Error:  5%
- Root Mean Squared  Error:  22%
- R Squared Error:  90% 

So, The accuracy of all used models was good. However, the best model is XGBoost regression because of its highest and greatest accuracy with a score(99%) which means it generalizes better than other models. Also, the Linear model is a great model choice since its computational inexpensive. The result of accuracy indicates that the model is generalized and has no overfitting. 

# Tools
•	**Environment**: Jupyter Notebook.

•	**Programming** Language: Python.

•	**Data processing**: Pandas, NumPy.

•	**Visualization**: Seaborn, Matplotlib.

•	**Modeling and Evaluation**: Scikit-learn.

# Communication
The presentation consists of different figures for communicating the analysis objectives and findings including:
![Capture1](https://user-images.githubusercontent.com/47436737/146244078-6b57eaba-2939-4433-8052-e05ee8c49edc.JPG)

