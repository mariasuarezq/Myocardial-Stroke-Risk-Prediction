# Myocardial Stroke Risk Prediction

Acute myocardial stroke is a type of acute coronary syndrome characterized by the sudden onset of ischemic distress (lack of blood supply) to a part of the heart muscle, caused by the acute and total obstruction of one of the coronary arteries that supply it. Myocardial stroke is the leading cause of death for both men and women worldwide. The main reason for this is that the primary risk of acute myocardial stroke lies in the pre-hospital phase, meaning before admission to the hospital; mortality during this phase exceeds 40%. Once admitted to the hospital, if done promptly (ideally within four hours), modern treatments such as angioplasty and thrombolysis enable a satisfactory recovery from the stroke, and complications are relatively uncommon.

We will use in this proyect the "Healthcare DataSet Stroke Data", where we can find features like gender, age, various diseases, and smoking status. Each row in the DataSet provides relavant information about the patient. The dataset includes 5110 records and 12 attributes.

## Objective
Since the labels in the data are discrete, the prediction falls into two categories: the patient has had a stroke or the patient hasn't had a stroke. Therefore, we have a classification problem.

## Table of Contents
The analysis is divided into four sections, saved in juypter notebooks in this repository as follows:
- [Identifying the problem and inspecting the data](#identifying-the-problem-and-inspecting-the-data)
- [Exploratory data analysis](#exploratory-data-analysis)
- [Data pre-processing](#data-pre-processing)
- [Predictive model](#predictive-model)


## Project

## [Notebook 1:](https://github.com/mariasuarezq/Myocardial-Stroke-Risk-Prediction/blob/main/NB1%20Identifying%20the%20problem%20and%20inspecting%20the%20data.ipynb) Identifying the problem and inspecting the data
In this notebook, I am becoming familiar with the data through data exploration techniques, using Python libraries such as Pandas and NumPy.

## [Notebook 2:](https://github.com/mariasuarezq/Myocardial-Stroke-Risk-Prediction/blob/main/NB2%20Exploratory%20data%20analysis.ipynb) Exploratory data analysis
In this notebook, I am becoming familiar with the data by employing data visualization techniques using Python libraries such as Pandas, Matplotlib and Seaborn.

## [Notebook 3:](https://github.com/mariasuarezq/Myocardial-Stroke-Risk-Prediction/blob/main/NB3%20Data%20pre-processing.ipynb) Data pre-processing
In this notebook, I employ feature selection to reduce high-dimensional data and utilize feature extraction techniques for the purpose of reducing dimensionality.

## [Notebook 4:](https://github.com/mariasuarezq/Myocardial-Stroke-Risk-Prediction/blob/main/NB4%20Predictive%20model.ipynb) Predictive model
In this notebook, I develop a predictive model using the Logistic Regression machine learning algorithm to forecast the diagnosis of a breast tumor. The diagnosis is a binary variable (the patient has had a stroke or not). Additionally, I build the predictive model employing K-NN, Random Forest, and SVM algorithms, and I compare the results across all of them.