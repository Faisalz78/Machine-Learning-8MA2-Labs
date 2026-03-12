# 📊 Data Quality & Preprocessing Assignment

## 📁 Dataset
This project uses the Netflix Titles Dataset, which contains information about movies and TV shows on Netflix such as title, country, director, release year, and date added.

---

## 🎯 Objective
The goal of this assignment is to apply data preprocessing techniques to improve data quality before analysis.

---

## ⚙️ Steps Performed

### 📥 Load Dataset
The dataset was loaded using pandas.

### 🔍 Check Data Types
The data types of all columns were inspected to understand the structure of the dataset.

### 🗓 Convert Data
The column `date_added` was converted to datetime format.

### ❓ Handle Missing Values
Missing values were detected and handled using
- Removing rows (`dropna`)
- Filling values with mean or median

### 📦 Detect Outliers
Outliers were detected using the IQR method and visualized using a boxplot.

### 🧮 Feature Preparation
A new feature year_added was extracted from the `date_added` column.

### 📏 Data Scaling
Two scaling techniques were applied
- Min-Max Normalization
- Standardization (Z-score)

### 🧠 PCA
Principal Component Analysis (PCA) was applied to reduce data dimensions while keeping the most important information.

---

## ✅ Conclusion
Data preprocessing improves dataset quality by
- handling missing values  
- detecting outliers  
- scaling data  
- reducing dimensionality using PCA