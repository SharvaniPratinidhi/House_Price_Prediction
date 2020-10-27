# House Price Prediction

The price of a property is dependent upon many factors including the amenities, location, type & size of property.
This projet aims at estimating the optimal price of the property using supervised machine learning techniques like regression and neural networks and identifying the characteristics of the property which have the a strong influence on the price.

## Environment
 Google Colaboratory
 
 Python 3.6 Libraries: 
  * Pandas 
  * Numpy
  * Matplotlib
  * Seaborn
  * Sklearn
  * Xgboost
  * Keras
  
## Data 
The data used for the analysis consists of the features of the listing including the target price.
This data was used for supervised training of the machine learning models to create a predictor for estimating the price of the properties.

### Data Preparation
The data preparation and cleaning steps included:
* Dropping columns with Null, single or irrelevant values
* Binning similar categorical attributes
* One hot encoding categorical attributes

### Data Exploration
Data Exploration included:
* Variable Identification
* Univariate Analysis
  1. Count Plot
  2. Distribution Chart
  3. Word Cloud
  
* Bivaraite Analysis
  1. Combinational Chart
  2. Violin Plot
  3. Bar chart
  4. Scatterplot

## Machine Learning Models
 The following models were implemented:
 * Linear Regression - Baseline Model
 * Linear Regression - Lasso Regularization
 * Linear Regression - Ridge Regularization
 * XGBoost 
 * Random Forest Regressor 
 * Neural Network with 3 Layers
 * Neural Network with 4 Layers
 * Neural Network with 4 Layers and Batch Normalization
 

## Evaluation

The models were compared using the following metrics:
* MAE
* RMSE
* R squared

The Random Forest Regressor gave the best accuray.
