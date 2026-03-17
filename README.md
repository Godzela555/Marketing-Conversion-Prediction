# Marketing-Conversion-Prediction
Machine Learning classification pipeline using PyCaret to predict marketing conversion based on customer loyalty, ad spend, and campaign channels.

# 🎯 Marketing Conversion Prediction

## 📌 Overview
This repository contains a machine learning classification project designed to predict customer conversion (`Conversion`). By analyzing marketing and customer attributes such as Ad Spend, Loyalty Points, and Campaign Channels, this project aims to identify the key drivers of successful marketing campaigns. The project leverages **PyCaret** to rapidly train, compare, and evaluate multiple classification algorithms.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** PyCaret (`pycaret.classification`), Scikit-Learn, XGBoost and LightGBM
* **Data Visualization:** Matplotlib, Seaborn

## 🚀 Key Features & Workflow
1. **Exploratory Data Analysis (EDA):** Visualized the relationship between conversion rates and key features (e.g., `LoyaltyPoints`, `AdSpend`, and `CampaignChannel`) using Seaborn's Violin plots and Boxen plots to uncover underlying trends.
2. **Data Preprocessing:** Utilized a preprocessed, rescaled, and balanced dataset (`Predict Conversion in Digital Marketing Dataset`) to ensure reliable model training.
3. **Automated Model Training:** Used PyCaret's automated classification pipeline to train and compare a wide variety of machine learning algorithms simultaneously.
4. **Model Evaluation:** Evaluated top-performing models (such as LightGBM and Ridge Classifier) using key metrics including Accuracy, Precision, Recall, and F0.5 Beta.

5. ## 📈 Results & Business Value
* The project successfully identifies which marketing channels and customer attributes yield the highest conversion rates.
* *("XGBoost achieved F0.5-score of 0.7765, making it the most robust model for this dataset.")*
