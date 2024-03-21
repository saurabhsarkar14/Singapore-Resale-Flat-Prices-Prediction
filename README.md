# Singapore-Resale-Flat-Prices-Prediction

## Introduction
This project aims to develop a machine learning model to predict the resale prices of flats in Singapore. The model utilizes historical data of resale flat transactions from the Singapore Housing and Development Board (HDB) spanning from 1990 to the present day.
## Problem Statement
Estimating resale prices accurately in the competitive Singapore housing market is challenging. This project addresses this issue by employing data preprocessing techniques, exploratory and multivariate analyses, and building machine learning models (Linear Regression, Decision Trees, K-Nearest Neighbours and XGBoost) to predict resale prices.
## Motivation
The resale flat market in Singapore is highly competitive, making it challenging to accurately estimate resale values. This project addresses the need for a predictive model that considers various factors influencing resale prices such as location, flat type, floor area, and lease duration.
## Features
Data Collection and Preprocessing: Importing necessary packages, reading and merging datasets, and performing initial data preprocessing tasks.
Exploratory Data Analysis (EDA): Gaining insights into the dataset through basic statistics, univariate and bivariate analyses, and the detection of aberrant or missing values.
Model Building and Evaluation: Constructing and evaluating Linear Regression, Decision Trees, K-Nearest Neighbours and XGBoost models for predicting resale prices.

## Data Source
The dataset used in this project was collected from [Data.gov.sg](https://beta.data.gov.sg/collections/189/view).

## Project Progress

### Data Preprocessing
**Importing Necessary Packages**
This step involves importing essential libraries like pandas, numpy, seaborn, and matplotlib for data manipulation and visualization.
**Reading and Merging Data**
Datasets are read and merged, combining relevant information for further analysis.
**Exploratory Data Analysis (EDA)**
EDA involves exploring the dataset through statistical measures and visualizations to understand patterns and trends.
**Multivariate Analysis**
Multivariate analysis encompasses exploring relationships between multiple variables, aiding in a more comprehensive understanding of the data.

## Model Building and Evaluation
**Linear Regression**
Linear Regression is employed to model the relationship between independent variables and resale prices. Model evaluation metrics include Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, R-squared Score, and Explained Variance Score.

**Decision Trees**
Decision Trees are utilized to model resale prices based on key features. Model evaluation follows similar metrics as in Linear Regression.

**K-Nearest Neighbours**
K-Nearest Neighbours is employed to predict resale prices based on the values of its k-nearest neighbors. Model evaluation metrics remain consistent across models.

**XGBoost**
XGBoost is employed for predicting resale flat prices. XGBoost is an ensemble learning algorithm that has proven effective in various machine learning tasks, providing high performance and efficiency. By including XGBoost in the model selection, the project aims to leverage its powerful gradient boosting capabilities to enhance the accuracy and predictive performance of the resale price prediction model.

## Deploying on Streamlit Cloud
The predictive model is now accessible via a Streamlit application hosted at the following link: https://singapore-resale-flat-prices-predicting.streamlit.app/
