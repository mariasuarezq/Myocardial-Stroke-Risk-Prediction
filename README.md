# Myocardial Stroke Risk Prediction

Breast cancer is a disease in which cells in the breast with abnormalities multiply uncontrollably and form tumors that, if not treated, can spread throughout the body and cause death. Cancerous cells begin to develop within the milk-producing ducts or lobules of the breast. Cancer at stage 0 (in situ) is not potentially fatal. Cancer cells can spread to nearby breast tissue (invasion), leading to nodules or thickening. Invasive cancers can spread to nearby lymph nodes or other organs (metastasis). Metastases can be deadly. 
In the 1990s, survival rates began to improve, when countries implemented early breast cancer detection programs associated with comprehensive treatment programs that included effective pharmacological treatments. In 2020, breast cancer was diagnosed in 2.3 million women worldwide, and 685,000 died from the disease. By the end of the same year, 7.8 million women who had been diagnosed with breast cancer in the previous five years were still alive, making it the most prevalent cancer in the world. 

We will use in this proyect the "Breast Cancer Wisconsin (Diagnostic) Data Set", where we can find features which are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The classification goal is to predict whether the patient diagnosis is malignant o benign. The features describe characteristics of the cell nuclei which are present in the image. The dataset includes 569 records and 32 attributes (ID, diagnosis and 30 real-valued input features). Ten real-valued features are computed for each cell nucleus.

## Objective
Since the labels in the data are discrete, the prediction falls into two categories: the patient has a malignant tumor or the patient has a benign tumor. Therefore, we have a classification problem.

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