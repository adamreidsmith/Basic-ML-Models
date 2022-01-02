# Basic ML Models
This repository contains basic implementations of a few machine learning algorithms as well as the preliminary data analysis involved.

# Installation
    $ git clone https://github.com/adamreidsmith/Basic-ML-Models
    $ cd Basic-ML-Models
    $ sudo pip3 install -r requirements.txt

# Description of Models

## MLR
A multiple linear regression (MLR) model was used to predict the fuel economy of vehicles given attributes of the vehicles, such as weight, engine displacement, and horsepower, which were found within the [Auto MPG Data Set](http://archive.ics.uci.edu/ml/datasets/Auto+MPG) from the UCI Machine Learning Repository.  Preliminary data analysis involved imputing missing values, inspecting relationships between variables, investigating potential new variables by combining the existing ones, and preparing the data for the MLR algorithm.  The MLR was carried out with the open source machine learning framework [PyTorch](https://pytorch.org).

## Logistic Regression
This binary classification model aims to predics whether an individuals annual income exceeds $\$$50,000 given characteristics about their education, ethnicity, working class, and a few others found in the [Adult Data Set](https://archive.ics.uci.edu/ml/datasets/adult) from the UCI Machine Learning Repository.  Preliminary data analysis involves investigation the relationships between given variables and income, adjusting variables to better suit the learning algorithm, and preparing the data types for the model.  The logistic regression model was carried out with the open source machine learning framework [PyTorch](https://pytorch.org).  Several measures were used to analyze the model's performance including a confusion matrix, $F_1$ score, and an [ROC curve](https://en.wikipedia.org/wiki/Receiver_operating_characteristic).

# License
[MIT](/LICENSE)