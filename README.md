# 🧠 Week 4 NSP Nexus Project – Predicting Employee Attrition

## 📌 Project Title:
**Predicting Employee Attrition using Machine Learning with IBM HR Analytics Dataset**

## 🎯 Objective:
Build a machine learning model to predict whether an employee is likely to leave the company using HR data. The project includes preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

---

## 🗃️ Dataset:
- Source: [Kaggle – IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Description: This dataset contains employee-related data such as age, department, job role, income, and attrition status.

---

## 🛠️ Tools & Libraries Used:
- Python
- Google Colab
- `pandas`, `numpy` – Data handling
- `matplotlib`, `seaborn` – Data visualization
- `scikit-learn` – Machine Learning models
- `imbalanced-learn` – For SMOTE (class imbalance)

---

## 🧪 Steps Followed:

### 1️⃣ Load the Dataset
- Loaded using `pandas.read_csv()`
- Basic checks: `.head()`, `.shape`, `.info()`

### 2️⃣ Explore the Data
- Used `.describe()`, `.value_counts()` to understand distributions
- Focused on key columns like `Attrition`, `JobRole`, `OverTime`

### 3️⃣ Data Preprocessing
- Categorical encoding using `LabelEncoder` / `OneHotEncoder`
- Feature scaling with `StandardScaler`
- Used **SMOTE** to handle class imbalance

### 4️⃣ Exploratory Data Analysis (EDA)
- Visualizations with countplots, boxplots, and heatmaps
- Found attrition trends by department, income, and job role

### 5️⃣ Model Building
- Trained three models: **Logistic Regression**, **Random Forest**, **XGBoost**
- Used `train_test_split` and `cross_val_score` for evaluation

### 6️⃣ Model Evaluation
- Used metrics: Accuracy, Precision, Recall, F1-Score
- Focused on **Recall** to catch employees likely to leave

### 7️⃣ Feature Importance
- Found top features: `OverTime`, `JobSatisfaction`, `MonthlyIncome`
- Helps HR focus on real attrition risks

---

## 📊 Key Insights:
- Employees doing **overtime** or having **low job satisfaction** are more likely to leave.
- Improving **work-life balance** and **compensation** can help HR retain talent.

---

## 📹 Video Demo:
[Include your YouTube or Google Drive link here if applicable]

---

## 📁 Folder Structure:
