# 🚖 Ride Hailing Fare Surge Prediction

## 📌 Project Overview

This project focuses on predicting ride fare surge using machine learning techniques on real-world ride-hailing data. The goal is to analyze various factors affecting surge pricing and build models that can accurately predict fare fluctuations.

---

## 📊 Dataset

The dataset used in this project is the **Uber and Lyft Dataset (Boston, MA)** available on Kaggle.

🔗 Dataset Link:
https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma

It includes important features such as:

* Distance
* Cab type (Uber/Lyft)
* Pickup & destination locations
* Surge multiplier
* Price
* Weather conditions

> ⚠️ Note: Due to file size limitations, the dataset may not be fully available in this repository. Please use the above Kaggle link to download it.

---

## ⚙️ Workflow

The project follows a structured machine learning pipeline:

1. Data Cleaning & Preprocessing
2. Handling Missing Values
3. Feature Engineering
4. Train-Test Split
5. Dimensionality Reduction using PCA
6. Model Training & Evaluation

---

## 🧠 Models Used

To ensure robust performance, multiple models were implemented:

* Linear Regression
* K-Nearest Neighbors (KNN)
* Random Forest Regressor
* Gradient Boosting Regressor

These models cover different learning approaches such as linear, instance-based, and ensemble methods.

---

## 🔍 Key Concepts Applied

* **PCA (Principal Component Analysis):**
  Used to reduce dimensionality and handle multicollinearity.

* **Avoiding Data Leakage:**
  PCA was applied after train-test split and fitted only on training data to ensure fair evaluation.

* **Model Evaluation Metrics:**
  Performance was evaluated using appropriate regression metrics.

---

## 📁 Project Structure

* `Ride_Surge_Prediction_FINAL_PRO.ipynb` → Main notebook containing complete implementation
* `dirty_dataset.csv` → Dataset used for training and testing
* `README.md` → Project documentation

---

## 📈 Conclusion

This project demonstrates how proper preprocessing, dimensionality reduction, and model selection can significantly improve prediction performance while maintaining model reliability and avoiding data leakage.

---

