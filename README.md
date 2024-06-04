# Breast Cancer Dataset Analysis

# 📊 📈 📉 Introduction

Breast cancer is one of the most prevalent cancers affecting women worldwide. Early detection and accurate diagnosis are crucial for effective treatment and improved patient outcomes.This project shows the analysis of a breast cancer dataset which was sourced from kaggle, drawing insights from the morphological characteristics of the cells and their implication on the growth behaviour. 

# Data Cleaning

The dataset was relatively clean, containing no null values and no duplicated entries. To make the data more understandable, the 'M' and 'B' labels in the 'diagnosis' column were renamed to 'Malignant' and 'Benign' to communicate more clearly.

# 🔍 Exploratory Data Analysis (EDA)

The EDA process showed a strong relationship between the area mean and radius mean of the cancer cells, as well as a strong relationship between the perimeter mean and radius mean of the cells. Malignant cancer cells were also found to have much higher area and radius mean than Benign cells

# Modeling
# Feature Scaling and Categorical Encoding

In order to get the data ready for modeling I used the StandardScaler to standardize the necessary columns, reducing them to a scale between 0 and 1 and also carried out categorical encoding, using the Label Encoder to transform the diagnosis column.

# Model Selection

Several classifiers were trained to classify the Cancer cells into Malignant and Benign cells, with the RandomForest Classifier emerging as the best performing model with an accuracy of 96% and recall percentage of 99% for Benign cells and 93% for Malignant cells.

#Hyperparameter Tuning

The GridSearchCV was used to find the best parameters for the RandomForest Classifier in order to increase the model performance, producing a final recall percentage of 99% for Benign cells and 93% for Malignant cells.

