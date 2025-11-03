# 🔋 Sodium-ion Battery Analysis using Machine Learning

![Progress](https://img.shields.io/badge/Status-In%20Progress-yellow)

**🟢 Currently Active** – Core models are implemented and functional. Improvements and visualizations are in progress.

---

## 📌 Objectives

- Classify battery cycle life into categories (e.g., low, medium, high).
- Predict the **peak discharge capacity** using regression models.
- Improve accuracy and interpretability over simple decision tree methods.

---

## 🧠 Machine Learning Workflow

### 1. **Data Preprocessing**
- Cleaned and normalized raw battery dataset.
- Feature selection based on correlation and importance.
- Addressed non-linear feature relationships using appropriate models.

### 2. **Class Balancing**
- Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to handle class imbalance in cycle life classification.

### 3. **Model Training**
#### 🔹 Classification:
- **Random Forest Classifier**
- **XGBoost Classifier**

#### 🔹 Regression (for Peak Discharge Capacity):
- **Random Forest Regressor**
- **XGBoost Regressor**

### 4. **Evaluation Metrics**
- **Classification:** Accuracy, F1 Score, Precision, Confusion Matrix
- **Regression:** RMSE (Root Mean Squared Error), R² Score

---

## 🧪 Results

- Achieved high classification accuracy after SMOTE balancing.
- Regression models provided low RMSE and high R², showing good generalization to unseen data.

---

## 🛠 Tools & Libraries

- Python
- scikit-learn
- XGBoost
- imbalanced-learn (for SMOTE)
- NumPy, Pandas
- Matplotlib, Seaborn

---

## 🚀 Future Work

- Add LSTM or GRU models to analyze time-series battery performance.
- Integrate model with battery management systems.
- Visualize predictions via a web dashboard.

---

## 🤝 Authors

- [Harish R](https://www.linkedin.com/in/harish-r-8b68a333b/)
- [Mauli Rajguru](https://www.linkedin.com/in/maulir/)
- [Shivani K C](https://www.linkedin.com/in/shivani-k-c/)
- [Vishnu K Mahesh](https://www.linkedin.com/in/vishnu-mahesh-9171a9307/)
---

## 📄 License

This project is licensed under the MIT License.
