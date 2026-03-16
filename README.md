# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using machine learning techniques. The goal is to analyze housing data and build a regression model that can estimate the sale price of houses based on various features such as area, quality, number of rooms, and year built.

The dataset used in this project comes from the Kaggle competition **House Prices: Advanced Regression Techniques**.

---

## 👩‍💻 Author

**Vanshika Sharma**

---

## 📊 Problem Statement

Real estate pricing depends on multiple factors such as location, house size, number of rooms, and construction quality. Manually estimating prices is difficult.

This project builds a machine learning model that can predict house prices based on historical housing data.

---

## 📂 Dataset

The dataset contains detailed information about houses including:

* Lot size
* Year built
* Number of rooms
* Garage size
* Basement area
* Overall quality
* Living area

### Dataset Files

* `train.csv`
* `test.csv`
* `data_description.txt`

---

## 🛠️ Technologies Used

| Tool         | Purpose                   |
| ------------ | ------------------------- |
| Python       | Programming language      |
| Pandas       | Data manipulation         |
| NumPy        | Numerical operations      |
| Matplotlib   | Data visualization        |
| Seaborn      | Statistical visualization |
| Scikit-learn | Machine learning models   |

---

## 🔎 Machine Learning Workflow

### 1️⃣ Data Loading

The dataset was loaded using Pandas.

### 2️⃣ Data Exploration

Basic dataset information was analyzed including:

* number of rows and columns
* missing values
* data types

### 3️⃣ Data Cleaning

Missing values were handled by:

* removing columns with excessive missing values
* filling numerical columns with median values

### 4️⃣ Exploratory Data Analysis (EDA)

Visualization techniques were used to understand relationships between features and house prices.

Correlation analysis helped identify the most important variables affecting house prices.

### 5️⃣ Feature Selection

Important features selected for the model include:

* OverallQual
* GrLivArea
* GarageCars
* TotalBsmtSF
* 1stFlrSF
* FullBath
* TotRmsAbvGrd
* YearBuilt

These features showed strong correlation with house prices.

### 6️⃣ Train-Test Split

The dataset was divided into:

* 80% training data
* 20% testing data

This ensures the model is evaluated on unseen data.

### 7️⃣ Model Training

A **Linear Regression model** was used to learn the relationship between house features and their prices.

### 8️⃣ Model Prediction

The trained model was used to predict house prices for the test dataset.

### 9️⃣ Model Evaluation

Model performance was evaluated using **Root Mean Squared Error (RMSE)**.

Lower RMSE indicates better prediction accuracy.

---

## 📈 Results

The model successfully learned relationships between house features and prices. Important features such as **overall house quality and living area** significantly influenced price predictions.

---

## 📊 Visualization

Scatter plots and correlation heatmaps were used to visualize relationships between variables and evaluate model performance.

---

## 📁 Project Structure

```
house-price-prediction
│
├── train.csv
├── test.csv
├── house_price_prediction.ipynb
├── README.md
```

---

## 🚀 Future Improvements

Possible improvements for this project include:

* Feature scaling
* Using advanced models such as Random Forest
* Hyperparameter tuning
* Feature importance analysis
* Using XGBoost for better prediction accuracy

---

## 📚 Key Learnings

This project helped understand:

* Data preprocessing
* Exploratory Data Analysis
* Feature selection
* Regression models
* Model evaluation techniques

---

## ⭐ Conclusion

This project demonstrates how machine learning can be used to predict house prices using real-world datasets. It provides hands-on experience with the complete data science workflow from data preprocessing to model evaluation.
