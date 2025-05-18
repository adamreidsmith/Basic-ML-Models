# Basic ML Models
This repository contains basic implementations of a few machine learning algorithms as well as the preliminary data analysis involved.

# Description of Models

## Linear Regression
In this project, we implement a linear regression model to predict the number of crimes in Calgary's communities based on the [Calgary Crimes dataset](https://data.calgary.ca/Health-and-Safety/Community-Crime-Statistics/78gh-n26t/about_data) using various attributes such as the crime type, number of community residents, and date range. Preliminary data analysis involved imputing missing values, numerical encoding of categorical variables, investigating potential new variables by combining the existing ones, and preparing the data for the LR algorithm.  The MLR was carried out with the open source machine learning framework [scikit-learn](https://scikit-learn.org/stable/).

## MLR
A multiple linear regression (MLR) model was used to predict the fuel economy of vehicles given attributes of the vehicles, such as weight, engine displacement, and horsepower, which were found within the [Auto MPG Data Set](http://archive.ics.uci.edu/ml/datasets/Auto+MPG) from the UCI Machine Learning Repository.  Preliminary data analysis involved imputing missing values, inspecting relationships between variables, investigating potential new variables by combining the existing ones, and preparing the data for the MLR algorithm.  The MLR was carried out with the open source machine learning framework [PyTorch](https://pytorch.org).

## Logistic Regression

### Income
This binary classification model aims to predics whether an individuals annual income exceeds $50,000 given characteristics about their education, ethnicity, working class, and a few others found in the [Adult Data Set](https://archive.ics.uci.edu/ml/datasets/adult) from the UCI Machine Learning Repository.  Preliminary data analysis involves investigation the relationships between given variables and income, adjusting variables to better suit the learning algorithm, and preparing the data types for the model.  The logistic regression model was carried out with the open source machine learning framework [PyTorch](https://pytorch.org).  Several measures were used to analyze the model's performance including a confusion matrix, F-1 score, and an [ROC curve](https://en.wikipedia.org/wiki/Receiver_operating_characteristic).

### Crimes
In this project, we implement a logistic regression model and a fully-connected neural network to predict the category of crimes in Calgary's communities based on the [Calgary Crimes dataset](https://data.calgary.ca/Health-and-Safety/Community-Crime-Statistics/78gh-n26t/about_data). Preliminary data analysis involved imputing missing values, numerical encoding of categorical variables, investigating potential new variables by combining the existing ones, and preparing the data for the machine learning algorithms. The logistic regression was carried out with the open source machine learning framework [scikit-learn](https://scikit-learn.org/stable/), whereas [TensorFlow](https://www.tensorflow.org) was used to implement the fully-connected neural network.


## SVM
The [data](https://archive.ics.uci.edu/ml/datasets/adult) used in this binary classification model is the same as that for the logistic regression model.  The preliminary data analysis proceeds the same as well, except that missing values are imputed with a KNN imputer using the machine learning library [scikit-learn](https://scikit-learn.org/stable/).  The model is created with scikit-learn and a grid search over the classifier's C and gamma values is implemented in an effort to optimize the model.  Several measures of the models performance are computed, and the ROC curve from this model is compared to that of the logistic regression model.  Both models are found to perform similarly with little difference in accuracy and F-1 score.

# Technologies Used
 * [Jupyter Notebook](https://jupyter.org)
 * [PyTorch](https://pytorch.org)
 * [TensorFlow] (https://www.tensorflow.org)
 * [Scikit-learn](https://scikit-learn.org/)
 * [Pandas](https://pandas.pydata.org)
 * [Seaborn](https://seaborn.pydata.org)
 * [Numpy](https://numpy.org)
 * [Matplotlib](https://matplotlib.org)

# Installation
    $ git clone https://github.com/adamreidsmith/Basic-ML-Models
    $ cd Basic-ML-Models
    $ sudo pip3 install -r requirements.txt

# License
[MIT](/LICENSE)
