# Breast Cancer Dataset Analysis

# 📊 📈 📉 Introduction

Breast cancer is one of the most prevalent cancers affecting women worldwide. Early detection and accurate diagnosis are crucial for effective treatment and improved patient outcomes. This project shows the analysis of a breast cancer dataset which was sourced from kaggle, drawing insights from the morphological characteristics of the cells and their implication on the growth behaviour. This project also involved training a Machine Learning model to classify cancer cells in patients into Malignant and Benign. Correctly classifying cancer cells is important as early detection of Malignant cells can significantly improve the prognosis and chances of survival. Accurate classification of Benign tumours can prevent unnecessary panic in patients, and prevent them from undergoing unnecessary treatments.

# 🧹 Data Cleaning

The dataset was relatively clean, containing no null values and no duplicated entries. To make the data more understandable, the 'M' and 'B' labels in the 'diagnosis' column were renamed to 'Malignant' and 'Benign' to communicate more clearly.

# 🔍 Exploratory Data Analysis (EDA)

The EDA process showed a strong relationship between the area mean and radius mean of the cancer cells, as well as a strong relationship between the perimeter mean and radius mean of the cells. Malignant cancer cells were also found to have much higher area and radius mean than Benign cells

# 🤖 Modeling
# Feature Scaling and Categorical Encoding

In order to get the data ready for modeling I used the StandardScaler to standardize the data and also carried out categorical encoding, using the Label Encoder to transform the diagnosis column.

# Model Selection and Training

I trained a model to classify the cancer tumours into Malignant and Benign using a range of classification algorithms. The RandomForestClassifier was the best performing model with an accuracy of 96% and recall percentage of 99% for Benign cells and 93% for Malignant cells.

# 💡 Conclusion
The insights and model developed in this project can help to increase the survival chances of cancer patients as accurately classifying their cancer tumors can help patients to get the appropriate treatment required to tackle their cases and prevent unnecessary treatment as the case may be

