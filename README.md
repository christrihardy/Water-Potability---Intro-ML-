# Water Potability Model - Intro to ML Project

## Objective
Membuat model machine learning untuk memprediksi klasifikasi water potability

## Dataset
Dataset "Water Quality" dari [Kaggle](https://www.kaggle.com/datasets/adityakadiwal/water-potability?datasetId=1292407&sortBy=voteCount)

## Data Preparation & Preprocessing
1. Input-Output Split
2. Train - Test split
3. Impute missing values
4. Standardizing data
5. Balance the data with Oversampling

## Modelling 
Metric: Precision
Model yang digunakan:
- KNN
- Random Forest
- SVM
- XGBoost
- Naive Bayes
- Logistic Regression

Setelah dilatih di data Train dan diuji di data Validation, 2 model terbaik adalah KNN dan Random Forest

## Hyperparameter Tuning
Model terbaik adalah **Random Forest** dengan Precision: 65% dengan peningkatan 1.92% dari baseline

## Final Model
![image](https://github.com/christrihardy/Water-Potability---Intro-ML-/assets/122888994/7358a964-9794-4342-9e3d-7960ff3ed005)

![image](https://github.com/christrihardy/Water-Potability---Intro-ML-/assets/122888994/4ee0f8dc-8c4a-46af-9074-b3ec2fc7baf8)

Ada penurunan precision menjadi 63% di data Test

