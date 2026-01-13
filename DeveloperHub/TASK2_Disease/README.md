# ❤️ Heart Disease Prediction System Using Machine Learning

## 📌 Project Overview
This project implements a **Heart Disease Prediction System** using supervised machine learning techniques.  
The objective is to analyze patient health data, identify important clinical factors, and predict whether a person is likely to have heart disease.

The project covers the **complete machine learning pipeline**, including:
- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Model training
- Model evaluation
- Feature importance analysis

---

## 🎯 Objective
- Understand trends and patterns in heart disease data
- Build a classification model to predict heart disease presence
- Evaluate model performance using standard classification metrics
- Identify key features influencing predictions

---

## 📊 Dataset
- **Dataset:** Heart Disease Dataset (`heart.csv`)
- **Source:** Public medical dataset (commonly used for ML research)
- **Target Variable:** `target`
  - `0` → No heart disease  
  - `1` → Presence of heart disease  

### Key Features
| Feature | Description |
|------|------------|
| age | Age of patient |
| sex | Gender |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| thalach | Maximum heart rate achieved |
| oldpeak | ST depression induced by exercise |
| ca | Number of major vessels |
| thal | Thalassemia |
| target | Heart disease presence |

---

## 🛠️ Technologies Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🔍 Project Workflow

### 1️⃣ Data Loading & Initial Exploration
- Loaded dataset using pandas
- Inspected structure using `.info()` and `.head()`
- Analyzed statistical properties using `.describe()`

---

### 2️⃣ Data Cleaning & Preprocessing
- Handled missing values (median for numerical, mode for categorical)
- Removed duplicate records
- Prepared data for machine learning models

---

### 3️⃣ Exploratory Data Analysis (EDA)
- Target variable distribution analysis
- Feature distribution using histograms
- Outlier detection using box plots
- Feature-to-target relationship analysis
- Correlation heatmap for numerical features

---

### 4️⃣ Model Training
Two classification models were implemented:

- **Logistic Regression** (Primary Model)
- **Decision Tree Classifier** (Optional comparison)

Data was split into training and testing sets using stratified sampling.

---

## 📈 Model Evaluation Metrics
The models were evaluated using:

- **Accuracy Score**
- **Confusion Matrix**
- **ROC Curve**
- **AUC Score**

These metrics help assess classification performance and class separation ability.

---

## 📊 Visualizations
The project includes:
- Target distribution plots
- Feature histograms
- Box plots for outlier detection
- Confusion matrix visualization
- ROC curve for performance evaluation
- Feature importance bar charts

---

## 🔑 Feature Importance Analysis
- Logistic Regression coefficients were analyzed to determine influential features
- Decision Tree feature importance scores were also examined

### Key Influential Features
- Chest pain type (`cp`)
- Maximum heart rate achieved (`thalach`)
- ST depression (`oldpeak`)
- Number of major vessels (`ca`)

These features are clinically significant and align with known medical knowledge.

---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
