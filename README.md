# Intelligent EARTH: ML Applications in the Earth Sciences
This repository contains the workshop materials for Intelligent EARTH workshop in DLSU Physics Department. 

This workshop aims to upskill Physics graduate students on the following: (1) Programming for Data Analysis, (2) Geospatial Data Analysis, (3) Machine Learning Methodologies for the Earth Sciences. The workshop will primarily utilize Google Colaboratory with Python 3.xx as its kernel.

The content of the folders will be uploaded every after session, restricted to the attendance of participants.

# Schedule of Activities

| Date | Time | Session Title | Key Words |
| :---: | :---: | :--- |  :---: |
| 2024-11-06 | AM 0900-1200 | [Session 1: Programming for Data Analysis](https://github.com/castred/Intelligent-EARTH/tree/main/session-1) | `python` `numpy` `pandas` `matplotlib` |
| 2024-11-06 | PM 1300-1600 | [Session 2: Methods for Geospatial Data Analysis](https://github.com/castred/Intelligent-EARTH/tree/main/session-2) | `geopandas` `scipy` `statsmodels` `pyKrige` |
| 2024-11-19 | AM 0900-1200 | [Session 3: Overview of Machine Learning](https://github.com/castred/Intelligent-EARTH/tree/main/session-3) | `scipy` `scikit-learn` `xgboost` |
| 2024-11-19 | PM 1300-1600 | [Session 4: Traditional Machine Learning Algorithms](https://github.com/castred/Intelligent-EARTH/tree/main/session-4) |  `scikit-learn` `sckit-image` `xarray`  |
| 2024-11-27 | AM 0900-1200 | [Session 5: Introduction to Deep Learning](https://github.com/castred/Intelligent-EARTH/tree/main/session-5) | `scipy` `optuna` `scikit-learn` |
| 2024-11-27 | PM 1300-1600 | [Session 6: Model Tuning, xAI, & Current Trends](https://github.com/castred/Intelligent-EARTH/tree/main/session-6) | `pytorch` |

<br> </br>

# Outline of Contents

<br> </br>

## Session 1: Programming for Data Analysis
This session intends to review/introduce the participants with the common techniques in Data Analysis using Python and its common data processing libraries.

The following topics will be covered:

* Introduction to Computational Thinking
* Python Objects and Functions
* NumPy: Numerical Python
* Data Manipulation using Pandas
* Basic Data Visualization using MatplotLib

<br> </br>

## Session 2: Methods for Geospatial Data Analysis
This session aims to narrow the discussion of data analysis to geospatial data structures and the fundamental methods to make meaning out of geospatial data. The main tool remains to be Python but with the addition of geoprocessing-specific libraries.

The following topics will be covered:

* Introduction to Geospatial Data: Collection and Structure
* Accessing, Processing, and Visualizing Geospatial Data
  - Vector Data
  - Raster Data
  - Point Cloud Data
* Overview of Geographic Information Systems
* Geostatistical Methods
  - 2D Interpolation
  - Variogram
  - Krigging
* Time Series Analysis & Forecasting
  - Time Series Decomposition
  - Autoregressive Model
  - Moving Average Model
  - ARIMA Model
  - Prophet Model

<br> </br>

## Session 3: Overview of Machine Learning
This section contains materials on the introduction to Machine Learning and its applications to Earth Sciences. This will help participants understand the different types of learning tasks and the procedural steps in building machine learning models.

The following topics will be covered:

* Overview of Machine Learning
* Importance of Machine Learning targeted towards Earth Science
* Usability of Machine Learning
* Software to Support Machine Learning
* Types of Learning Tasks and its Applications
  - Supervised Learning
  - Unsupervised Learning
  - Reinforcement Learning
* Machine Learning Pipeline
  - Download the training data
  - Exploratory data analysis
  - Extracting training data from tabular dataset
  - Extracting training data from raster dataset
  - Training and inference of tabular and raster dataset
  - Metrics and model evaluation

<br> </br>

## Session 4: Traditional Machine Learning Algorithms
This section expands on the different learning tasks by discussing an array of traditional machine learing algrithms that can be used to tackle specific machine problems. The participants will learn how to implement and train machine learning models using various algorithms, in the context of Earth Science.

The following topics will be covered:

* Supervised Learning Algorithms
  - Linear Regression
  - Logistic Regression
  - k-Nearest Neighbor Classification
  - Naive Bayes Classification
  - Support Vector Machine
  - Decision Trees
  - Random Forest
  - Gradient Boosted Trees
* Unsupervised Learning Algorithms
  - K-Means Clustering
  - Hierarchical Agglomerative Clustering
  - Density-Based Spatial Clustering of Applications with Noise
  - Principal Component Analysis

<br> </br>

## Session 5: Introduction to Deep Learning
This section moves from traditional ML algorithms to those that have resulted from the advent of Artificial Neural Networks. The participants get acquainted with concepts involved in ANN together with the different architectural cofigurations; and how to build and train them.

* Overview of Deep Learning
* Deep Learning Applications for Earth Sciences
* Basics of Artificial Neural Networks
  - Loss Functions
  - Forward & Backpropagation
  - Optimization
* Different Deep Learning Architectures
  - Multilayer Perceptron Model
  - Convolutional Neural Network
  - Recurrent Neural Network
  - AutoEncoder Network

<br> </br>

## Session 6: Model Tuning, Explainable AI, & Current Trends
This section builds upon the previous section and intends to improve the performance of the ML models. The section focuses on techniques to tune the model by optimizing model parameters and hyperparameters. Lastly, it also tackles explainability of the built models in aid of better understanding the physical phenomenon being modeled.

* Overview of model tuning
* Overview of parameter optimization
* Exercise to optimize existing model
* Overview of model explainability and interpretability
* Current Trends and Research in Intelligent EARTH
