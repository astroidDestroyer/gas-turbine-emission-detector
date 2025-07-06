# Gas Turbine Emissions Analysis Project 🌍🔬

## Overview 📄
This project conducts a comprehensive analysis of a gas turbine's operational data to predict the total energy yield and understand the emission patterns of CO and NOx. The dataset, sourced from the UCI Machine Learning Repository, provides a detailed compilation of sensor readings that reflect the turbine's performance and environmental impact.

## Table of Contents 📚
- [Introduction](#introduction)
- [Data Collection](#data-collection)
- [Data Preprocessing and Cleaning](#data-preprocessing-and-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Predictive Modeling](#predictive-modeling)
- [Results and Discussion](#results-and-discussion)
- [Conclusions](#conclusions)
- [Getting Started](#getting-started)


## Introduction 👋
The goal of this project is to utilize machine learning techniques to forecast the energy output of a gas turbine based on various operational parameters. Through this analysis, we aim to identify key factors that influence energy efficiency and emissions, which are critical for optimizing turbine performance and reducing environmental footprints.

## Data Collection 🛰️
The analysis is based on data from a gas turbine located in Turkey during the year 2015. The dataset contains 7384 instances, each with 11 features that capture the atmospheric conditions, machine conditions, and emission levels at different timestamps.

## Data Preprocessing and Cleaning 🧹
Initial data inspection revealed a well-maintained dataset with no missing values. Feature examination was performed to understand the data types and distributions. Outliers were detected in the Turbine Inlet Temperature (TIT) and were treated appropriately to ensure they do not skew the analysis.

## Exploratory Data Analysis (EDA) 🔍
EDA was conducted to reveal underlying patterns and relationships in the data. I created univariate plots to understand the distribution of individual variables and bivariate plots to explore the correlations between the variables. The heatmaps confirmed strong correlations between Total Energy Yield (TEY) and features like Compressor Discharge Pressure (CDP), Turbine Inlet Temperature (TIT), and others.

## Predictive Modeling 📈
I built and compared three machine learning models: Linear Regression, Random Forest, and Decision Trees. Model selection was guided by the nature of the data and the project's regression problem framework. I performed hyperparameter tuning to optimize each model's performance and conducted a thorough evaluation to compare their predictive accuracy.

## Results and Discussion 💡
My modeling efforts highlighted that the Decision Tree algorithm provided the best performance after hyperparameter tuning, achieving impressive accuracy. The high correlation between some of the features and the target variable, as revealed in the EDA phase, contributed to the predictive success of the models.

## Conclusions 🎯
The project effectively demonstrated the application of machine learning in predicting the performance of a gas turbine. The insights gained could help in making informed decisions for operational efficiency and emission control. For future work, I would consider implementing ensemble methods and more advanced regression techniques like XGBoost to potentially improve predictive accuracy.

## Getting Started 🚀
To replicate the analysis, clone the repository, install the required Python packages, and run the Jupyter notebooks in order: `Phase1_Group91.ipynb` for data preprocessing and EDA, followed by `Phase2_Group91.ipynb` for predictive modeling.




