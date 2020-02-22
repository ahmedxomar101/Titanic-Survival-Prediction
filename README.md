# Titanic Survival Prediction
This project is part of Udacity Machine Learning Nanodegree projects.

## Table of Content
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Starting the Project](#starting-the-project)
    1. [Code](#code)
    2. [Run](#Run)
    3. [Data](#data)

## Project Overview

We will create decision functions that attempt to predict survival outcomes from the 1912 Titanic disaster based on each passenger's features, such as sex and age. We will start with a simple algorithm and increase its complexity until we are able to accurately predict the outcomes for at least 80% of the passengers in the provided data. 


## Prerequisites
This project uses the following software and Python libraries:

- [Python](https://www.python.org/download/releases/3.0/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

## Starting the Project

This project contains two files:

- `titanic_survival_exploration.ipynb`: This is the main file where you find all the work on the project.
- `titanic_data.csv`: The project dataset. Which is loaded in the notebook.


### Code

Template code is provided in the notebook `Titanic-Survival-Prediction.ipynb` notebook file. 

### Run

In a terminal or command window, navigate to the top-level project directory `Titanic-Survival-Prediction/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook titanic_survival_exploration.ipynb
```
or
```bash
ipython notebook titanic_survival_exploration.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser.

### Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the following attributes:

* **Features**
    - `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
    - `name` : Name
    - `sex` : Sex
    - `age` : Age
    - `sibsp` : Number of Siblings/Spouses Aboard
    - `parch` : Number of Parents/Children Aboard
    - `ticket` : Ticket Number
    - `fare` : Passenger Fare
    - `cabin` : Cabin
    - `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

* **Target Variable**

    - `survival` : Survival (0 = No; 1 = Yes)
