# 🤖 Adaptive Machine Learning Pipeline for Stock Prediction

## 🔍 Problem Statement

Most machine learning models require dataset-specific preprocessing and tuning. This project aims to build a robust system that can automatically handle different datasets and generate reliable predictions without manual intervention.

## 💡 Solution

Developed a dynamic machine learning pipeline that:

* Accepts datasets of varying structure and quality
* Automatically detects whether preprocessing is required
* Applies data cleaning only when necessary
* Trains multiple machine learning models
* Selects the best-performing model based on evaluation metrics
* Predicts future stock prices

## ⚙️ Models Used

* Linear Regression
* Random Forest
* K-Nearest Neighbors (KNN)

## 🔄 Pipeline Features

* Adaptive data cleaning (skips already-clean datasets)
* Flexible handling of different dataset formats
* Model comparison and selection
* Error-resistant workflow for diverse inputs

## 📊 Results

* Successfully handled multiple datasets without manual preprocessing
* Demonstrated consistent model selection based on performance
* Improved usability by reducing need for manual intervention

## 🛠️ Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib

## ▶️ How to Run

1. Upload dataset
2. Run pipeline script
3. View model performance and predictions

## 🚀 Key Insight

Automating preprocessing and model selection significantly reduces the effort required to deploy machine learning models on new datasets.
