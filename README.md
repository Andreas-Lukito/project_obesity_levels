# Project_Obesity_Levels

## 📌 Overview
**Project_Obesity_Levels** is a machine learning project that aims to predict a person’s nutritional status—ranging from underweight to obesity—based on their lifestyle. Inspired by rising health awareness post-COVID and alarming global obesity statistics, this project leverages data-driven insights to support early identification of unhealthy trends and promote healthier living.

## 📊 Problem Statement
According to WHO, in 2022:
- 2.5 billion adults were overweight,
- 890 million were living with obesity,
- 390 million were underweight.

This project aims to use lifestyle data and machine learning to classify individuals into different nutritional categories, which can help in mitigating health risks associated with malnutrition and obesity.

## 🧠 Machine Learning Approach

### ✅ Models Used
- **Random Forest Classifier** (baseline)
- **Neural Network (Sequential Model)** (proposed)

### 🛠️ Techniques Applied
- Data preprocessing and cleaning
- Feature scaling using `RobustScaler` and `StandardScaler`
- Outlier handling with Winsorization
- Correlation and multicollinearity checks using VIF
- Hyperparameter tuning using `GridSearchCV`
- Model evaluation using precision, recall, F1 score, and accuracy

## 🧪 Dataset
The dataset includes various lifestyle and health-related features such as:
- Physical activity
- Eating habits
- Water intake
- Screen time
- Smoking and alcohol habits

> 📁 Path: `./Dataset/Obesity_data.csv`

## 🔍 Results
The proposed neural network outperformed the baseline random forest classifier in terms of accuracy and other evaluation metrics, showing promise in using deep learning to classify obesity levels more effectively.

## 🧰 Libraries Used
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `keras`, `tensorflow`
- `feature_engine` (for Winsorizer)
- `statsmodels` (for VIF calculations)

```bash
jupyter notebook MachineLearning_AOL_Code.ipynb
