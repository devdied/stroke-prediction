# Stroke Prediction

## Introduction 

This project utilizes the Stroke Prediction Dataset, which can be accessed on Kaggle here: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset.  The dataset contains various categories of information, including age, gender, glucose level, hypertension, and more. We aim to analyze this dataset, clean the data, create visualizations, perform correlation test, and build a machine learning model to predict stroke occurrence.

Project Objectives
1.	Data Cleaning: To ensure the quality of our analysis, we will clean the dataset by handling null values and any other data inconsistencies.
2.	Data Visualization: We will create visualizations to gain insight into the dataset, including:
a.	Histogram of the age distribution
b.	Hypertension vs. no hypertension
c.	Stroke vs. no stroke
d.	Male vs. female distribution
3.	Correlation Analysis: We will perform correlation tests between different factors and the likelihood of stroke. Factors with low correlation to stroke will be excluded when building the machine learning model.
4.	Machine Learning Models: Utilizing scikit-learn, we will experiment with various machine learning models, including the Random Forest Classifier, Decision Tree, and Deep Learning Model . The model's performance will be evaluated based on accuracy.
5.	Resampling: We resampled the data to balance the dataset through SMOTE and Random Oversampler prior to building our models to investigate if this improves the prediction accuracy.
6.	Confusion Matrix: We will generate a confusion matrix to further evaluate the model's performance.
7.	Web Application: A Flask web application will be created to showcase the project's findings. Users can input data such as age, BMI, and hypertension to predict stroke occurrence. The Flask web application will deploy the machine learning model that yielded that highest accuracy: Random Forest Classfier at 99%. 

## Credits:
* For Smote oversampler:
    - <https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification>
    - <https://www.blog.trainindata.com/overcoming-class-imbalance-with-smote>
