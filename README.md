# 🧠 Chronic Kidney Disease Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting **Chronic Kidney Disease (CKD)** using machine learning techniques. Early detection of CKD can significantly improve patient outcomes, and this project aims to build an accurate predictive model using patient health data.

---

## 🎯 Objective

* Analyze patient medical data to identify key risk factors for CKD
* Build and compare multiple machine learning models
* Select the best-performing model for prediction
* Provide actionable insights for early diagnosis

---

## 📊 Dataset

The dataset contains medical attributes such as:

* Age
* Blood Pressure
* Specific Gravity
* Albumin
* Sugar
* Hemoglobin
* Serum Creatinine
* And more...

📁 Files used:

* `Training_CKD_dataset.csv`
* `Testing_CKD_dataset.csv`

---

## ⚙️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn
  * XGBoost (optional)

---

## 🔍 Project Workflow

### 1. Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Feature scaling
* Outlier detection

### 2. Exploratory Data Analysis (EDA)

* Univariate & Bivariate analysis
* Correlation heatmap
* Data distribution visualization

### 3. Feature Engineering

* Feature selection
* Encoding techniques
* Scaling

### 4. Model Building

Models implemented:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting / XGBoost
* Support Vector Machine

### 5. Model Evaluation

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

### 6. Model Optimization

* Hyperparameter tuning using GridSearchCV / RandomizedSearchCV

### 7. Final Model

* Best model selected based on performance
* Tested on unseen dataset

---

## 📈 Results & Insights

* Identified key medical indicators influencing CKD
* Achieved high model performance using ensemble methods
* Demonstrated importance of features like:

  * Serum Creatinine
  * Hemoglobin
  * Blood Pressure

---

## 💾 Model Deployment (Optional)

The trained model can be deployed using:

* Streamlit
* Flask API

---

## 📁 Project Structure

```
CKD-Prediction-ML/
│
├── data/
│   ├── Training_CKD_dataset.csv
│   ├── Testing_CKD_dataset.csv
│
├── notebook/
│   └── CKD_Prediction_ML.ipynb
│
├── model/
│   └── ckd_model.pkl
│
├── requirements.txt
├── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/CKD-Prediction-ML.git
```

2. Navigate to project folder:

```bash
cd CKD-Prediction-ML
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the notebook:

```bash
jupyter notebook
```

---

## 🔮 Future Improvements

* Use Deep Learning models (ANN, LSTM)
* Deploy as a web application
* Integrate real-time hospital data
* Improve model explainability using SHAP

---

## 👨‍💻 Author

**Krishanu Santra**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!
