# UDACITY Data Scientist Nanodegree

# Project Detail
## Aeroplane_Severity_Prediction
Predicting the severity of airplane accidents based on past accidents
#### You can find more details about the study in my blog post at [Here](https://hr8077677.medium.com/the-severity-of-airplane-accidents-305136e495b8)
Flying has been the go-to mode of travel for years now; it is time-saving, affordable, and extremely convenient. According to the FAA, 2,781,971 passengers fly every day in the US, as in June 2019. Passengers reckon that flying is very safe, considering strict inspections are conducted and security measures are taken to avoid and/or mitigate any mishappenings. However, there remain a few chances of unfortunate incidents.

### Installation
You need an installation of Python, plus the following libraries:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- scikit-learn

### Process Breakdown
- **Business Understanding :**  We are required to build Machine Learning models to anticipate and classify the severity of any airplane accident based on past incidents. With this, all airlines, even the entire aviation industry, can predict the severity of airplane accidents caused due to various factors and, correspondingly, have a plan of action to minimize the risk associated with them.  
**Question in focus:**
    1. Which factor mostly affects accident ?
    2. Did airplane score good in safety ?
    3. When was the last inspection and how it affected the accident ?

and last we will make a model to predict severity of airplane accidents

- **Data Understanding :** The dataset is supplied in the [HackerEarth Competition](https://www.hackerearth.com/challenges/competitive/airplane-accident-severity-hackerearth-machine-learning-),to find severity of a accidents
The dataset consists of certain parameters recorded during the incident⁠ such as cabin temperature, turbulence experienced, number of safety complaints prior to the accident, number of days since the last inspection was conducted before the incident, an estimation of the pilot’s control given the various factors at play, and the likes. 

- **Data Preparation:** We will try to find and remove anomalies like missing values and data inconsistencies. Also we will see which features affects the data using ensemble technique and how usind data visualization.
- **Modeling :** We will we using ensemble technique called **Gradient Boosting**. Gradient boosting does very well because it is a robust out of the box classifier (regressor) that can perform on a dataset on which minimal effort has been spent on cleaning and can learn complex non-linear decision boundaries via boosting.
- **Evaluation:**  Our metric for worthiness of the model would be the accuracy. We will first try to find the optimal hyper-parameters for our model using GridCV and crossValidation to find the minimum amount of loss

### File Description
The csv file is downloaded from HackerEarth. The jupyter notebook file contains codes of data preprocessing, data visualizations and a model prediciton of Severity of an airplane accident.

### Summary
In summary, We went through each and every steps of CRISP_DM, did different types of analysis on the data, visualized the data with different types of charts and trained the model with different types of machine learning models to predict the severity of airplane accident.
