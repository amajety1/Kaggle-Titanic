# Kaggle-Titanic

#  Survival Analysis with Titanic Data

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

**In this project we try to build a model capable of predicting whether a passenger on the Titanic survives or not based on the given data**




## 2. Installation <a name="installation"></a>

- Python versions 3.*.
- Python Libraries:
    - sklearn.
    - Pandas.
    - numpy.
    - matplotlib.


## 3. Data<a name="data"></a> 

There are around 1300 records of passengers available from  <a href="https://www.kaggle.com/competitions/titanic/data">this Kaggle</a> dataset.



## 4. Implementation <a name="model"></a> 
In this project, we use a Random Forrest Regressor, as well as hyperparameter tuning with RandomizedSearchCV to find the optimal parameters.




## 5. Result<a name="results"></a>
Without the use of RandomizedSearchCV to find optimal hyperparameters, accuracy of 84% was obtained. 
With the use of RandomizedSearchCV, an accuracy of 88% was obtained.
