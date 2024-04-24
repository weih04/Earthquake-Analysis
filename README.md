# SC1015 - Data Science Project - Earthquake Magnitude Prediction

Our Problem Statement : How can we optimise machine learning algorithms to help enhance earthquake magnitude prediction in Japan?

Our Goal : To harness our dataset for identifying patterns and relationships pertinent to earthquake magnitude prediction, aiming to minimise the adverse effects of earthquakes in Japan

## DataSets

### Kaggle 

1. Earthquake in Japan (USGS Earthquake Data in Japan since 2019) 
    - main dataset
2. Earthquakes in Japan (2001 - 2018)
    - used in EDA ONLY


## FCED_Team 6 Folder

### Datasets Folder: 

This folder contains the original earthquake dataset, cleaned dataset, supplementary dataset as well as images used in our whole project.

### Slides: FCED_Team 6

This is the set of slides we used for our presentation. It touches on our group’s motivation, problem and aim, data collection and preparation, basic Exploratory Data Analysis and Data Visualisation as well as the 3 Machine Regression Models with two other new techniques that we have utilised to draw our conclusions.

-Tan Wei Hui & Nicholas Tan

### Jupyter Notebook #1: Data Cleaning & Preparation

This notebook contains the code we used to identify and remove duplicates and outliers in our data set. For column with missing values, we have included codes to replace them with either the median value or NAN or a total removal. Additionally, there are new features are created / original features are removed. For example, by splitting up the time features, we have obtained 3 new features which are day, month, year and season respectively. Other new features are normalised_mag and mag_category. For more details, please view our video/notebooks.

-Nicholas Tan

### Jupyter Notebook #2: Exploratory Data Analysis & Data Visualisation

This notebook contains the code we used to showcase the potential relationships between the variables with magnitude. In this notebook, we observe relationship between location and magnitude and number of stations recorded with magnitude. Interestingly, we also saw “potential” relationship between time and magnitude, however, it was debunk as a myth. For more details, please view our video/notebooks.

-Tan Wei Hui

### Jupyter Notebook #3: Machine Learning

This notebook contains code used to predict earthquake magnitude through the use of 3 regression models (Linear Regression, Random Forest, Polynomial Regression).  We then proceeded to use 2 new techniques (Cross Validation & Hyperparameter tuning) to prevent cases of overfitting in our datasets. The evaluations of models are mainly done in common metre of Mean Square Error, which is an average of the squares of the errors. For more details, please view our video/notebooks.

-Nicholas Tan


## Conclusions

Though our model isn’t able to hit 100% accuracy in magnitude prediction, we could see improvements made. Theoretically, our model has enhanced  earthquake magnitude prediction. However, in reality it is not the case. In our model, we did not deal with the prediction of the exact time and location of earthquakes. Hence, these aspects combined, make every prediction essentially a probability, not a certainty. This underscores the inherent complexities and uncertainties in forecasting seismic events.


## References

https://www.kaggle.com/datasets/aerodinamicc/earthquakes-in-japan
https://www.kaggle.com/datasets/stpeteishii/earthquake-in-japan
https://twitter.com/imAdityaRathore/status/1745531019854221809
https://www.usgs.gov/faqs/can-you-predict-earthquakes
https://www.analyticsvidhya.com/blog/2022/01/different-types-of-regression-models/https://www.ibm.com/topics/random-forest#:~:text=Random%20forest%20is%20a%20commonly,both%20classification%20and%20regression%20problems.
https://scikit-learn.org/stable/modules/cross_validation.html
https://towardsdatascience.com/hyperparameter-tuning-explained-d0ebb2ba1d35
http://www.usarray.org/public/about/how


