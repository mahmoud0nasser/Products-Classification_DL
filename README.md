# Product Recommendation (Classification)

This project focuses on building a product recommendation system using classification techniques. The goal is to predict whether a customer will make a purchase based on various features such as age, gender, annual income, number of purchases, product category, time spent on the website, loyalty program participation, and discounts availed.

## Table of Contents
- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Building](#model-building)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
The project uses a dataset containing customer purchase data. The dataset includes features like age, gender, annual income, number of purchases, product category, time spent on the website, loyalty program participation, discounts availed, and purchase status. The objective is to classify whether a customer will make a purchase or not.

## Data Preprocessing
- **Handling Missing Values**: Missing values were filled with the mean of the respective columns.
- **Correlation Matrix**: A correlation matrix was generated to understand the relationships between different features.

## Exploratory Data Analysis (EDA)
- **Data Description**: The dataset contains 1500 entries with 9 features.
- **Correlation Heatmap**: A heatmap was plotted to visualize the correlation between features.

## Model Building
- **Libraries Used**: The project utilizes libraries such as `pandas`, `numpy`, `scikit-learn`, `tensorflow`, and `matplotlib`.
- **Model Architecture**: A neural network model was built using TensorFlow's Keras API. The model consists of multiple dense layers with dropout layers to prevent overfitting.
- **Training**: The model was trained using the preprocessed dataset with early stopping to prevent overfitting.

## Results
- **Classification Report**: The model's performance was evaluated using a classification report, which includes precision, recall, and F1-score.
- **Confusion Matrix**: A confusion matrix was generated to visualize the model's performance in terms of true positives, true negatives, false positives, and false negatives.

## Conclusion
The project successfully built a product recommendation system using classification techniques. The model was able to predict customer purchase behavior with reasonable accuracy. Further improvements can be made by tuning hyperparameters and experimenting with different model architectures.
