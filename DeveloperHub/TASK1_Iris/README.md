# 🌸 Iris Dataset Analysis & Visualization

## 📌 Project Overview
This project explores the **classic Iris dataset**, one of the most well-known datasets in machine learning.  
The aim is to **understand feature distributions, relationships, and outliers** through exploratory data analysis (EDA) and visualizations.

This project is a fundamental exercise in **data exploration and visualization**, preparing the dataset for potential predictive modeling tasks.

---

## 🎯 Objective
- Load and inspect the Iris dataset
- Perform summary statistics and data exploration
- Visualize feature distributions and relationships
- Identify outliers and trends among the three Iris species

---

## 📊 Dataset
- **Dataset Name:** Iris  
- **Source:** Seaborn / UCI Machine Learning Repository  
- **Samples:** 150  
- **Features:** 4 numerical features + 1 categorical target  
- **Target Variable:** `Species`  
  - `Iris-setosa`
  - `Iris-versicolor`
  - `Iris-virginica`

### Features
| Feature | Description |
|---------|------------|
| SepalLengthCm | Sepal length in centimeters |
| SepalWidthCm  | Sepal width in centimeters |
| PetalLengthCm | Petal length in centimeters |
| PetalWidthCm  | Petal width in centimeters |
| Species       | Iris species (target variable) |

---

## 🛠️ Technologies Used
- Python
- pandas
- numpy
- matplotlib
- seaborn

---

## 🔍 Project Workflow

### 1️⃣ Data Loading & Inspection
- Loaded dataset using `pandas`
- Explored dataset using `.info()`, `.head()`, and `.describe()`
- Checked for missing values and data types

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Feature distributions using **histograms**
- Outlier detection using **box plots**
- Feature relationships using **scatter plots**
- Summary statistics to understand central tendencies and variability

---

### 3️⃣ Visualizations
- **Scatter plots:** Visualize relationships between features (e.g., SepalLength vs PetalLength)
- **Histograms:** Show distribution of each feature
- **Box plots:** Detect outliers and compare feature ranges across species
- **Color-coded plots by species** to highlight separability

---

## 📈 Key Insights
- **Petal features** (length and width) clearly separate *Iris-setosa* from other species
- **Sepal features** show more overlap between species
- Some outliers exist in SepalWidth, but overall data is clean
- Feature relationships indicate which variables are more useful for classification tasks

---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn
