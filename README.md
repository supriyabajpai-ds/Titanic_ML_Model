# 🚢 Titanic Survival Prediction (Machine Learning Project)

## 📌 Problem Statement
Predict whether a passenger survived the Titanic disaster using machine learning.

---

## 📊 Dataset
- Source: Kaggle Titanic Dataset
- Rows: 891 passengers
- Features: Age, Sex, Fare, Cabin, Ticket, etc.

---

## ⚙️ Workflow

### 🔹 Data Cleaning
- Handled missing values in Age and Cabin
- Dropped irrelevant features (PassengerId, Name)

### 🔹 Feature Engineering
- Extracted **Title** from Name (Mr, Mrs, Miss, Master)
- Converted **Cabin into deck categories**
- Created **Ticket-based features**
- Generated **Age bins using pd.cut()**
- Created **Family Size feature**

### 🔹 Exploratory Data Analysis
- Heatmaps for correlation
- Boxplots for feature relationships

### 🔹 Model Building
- Logistic Regression → ~80% accuracy
- Random Forest → **~83% accuracy**

### 🔹 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-score

---

## 📈 Results
- Best Model: Random Forest Classifier
- Accuracy: **~83%**

---

## 🧠 Key Learnings
- Importance of feature engineering
- Handling missing data effectively
- Model comparison and evaluation

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Cross-validation
- Advanced models (XGBoost)

---

## 🛠️ Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
