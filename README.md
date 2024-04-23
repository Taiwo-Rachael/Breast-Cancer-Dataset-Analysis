# 📊 📈 Breast Cancer Dataset Analysis

## Introduction

Breast cancer is one of the most prevalent cancers affecting women worldwide. Early detection and accurate diagnosis are crucial for effective treatment and improved patient outcomes. This project shows the analysis of a breast cancer dataset which was sourced from kaggle, drawing insights from the morphological characteristics of the cells and their implication on the growth behaviour. 

## Data Cleaning

The dataset was relatively clean, containing no null values and no duplicated entries. To make the data more understandable, the 'M' and 'B' labels in the 'diagnosis' column were renamed to 'Malignant' and 'Benign' to communicate more clearly.

## 🔎 Exploratory Data Analysis (EDA)

The first step of the EDA was to check the statistical summary of the dataset, looking out for outliers. The next step was to check the distribution of the perimeter mean of the cancer cells, which revealed that the benign cancer cells fell between 40 and 120, while the malignant cells fell between 70 and 170 with those with perimeter mean above 180 being outliers. The distribution of the area mean showed malignant cells having mean between 450 and 1800, with those above 2000 being outliers.

The analysis showed a strong correlation between the area and radius means of the cells, as well as the perimeter and radius mean. The bigger perimeter and radius mean of the malignant cells were indications of larger tumour sizes and more aggressive growth behaviours.

## 💡 Conclusion

The insights from this analysis prove that early detection can prevent cancer cells from getting worse as regular screening can help detect abnormalities in cell size and shape, helping to detect malignant cells at an early stage.
 


