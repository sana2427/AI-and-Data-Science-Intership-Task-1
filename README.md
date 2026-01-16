#  Task 1: Data Handling with NumPy & Pandas (Foundations)

##  Overview
This repository contains the solution for Task 1: Data Handling with NumPy & Pandas, completed as part of my AI & Data Science Internship tasks.

---

##  Objective
The objective of this task is to build a strong foundation in **data loading, cleaning, inspection, and basic manipulation** using **NumPy** and **pandas**.  
This task focuses on understanding a dataset before applying any machine learning model.

---

##  Dataset
**Dataset Name:** Iris Dataset  
**Type:** Structured CSV dataset  

### Dataset Description
- Total Records: **150**
- Target Variable: **species**
  - Iris setosa
  - Iris versicolor
  - Iris virginica
- Features:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)

The Iris dataset is a classic dataset widely used for data analysis and machine learning tasks.

---

##  Tools & Technologies Used
- Python
- NumPy
- pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Approach

### 1️⃣ Data Loading
- Loaded the dataset using `pandas.read_csv()`
- Converted CSV data into a pandas DataFrame for easy manipulation

### 2️⃣ Data Inspection
Used the following pandas functions:
- `.shape` → to check dataset dimensions  
- `.info()` → to inspect data types and null values  
- `.columns` → to view column names  
- `.head()` → to preview initial rows  

### 3️⃣ Data Cleaning
- Checked for missing values using `.isnull().sum()`
- Filled missing numerical values using column means
- Detected and removed duplicate records using `.duplicated()` and `.drop_duplicates()`

### 4️⃣ Exploratory Data Analysis (EDA)
- Generated statistical summaries using `.describe()`
- Visualized feature distributions using **boxplots**
- Analyzed relationships between features and target classes using **pairplots**
- Identified important features influencing classification

### 5️⃣ NumPy Operations
- Converted pandas DataFrame to NumPy arrays
- Performed basic statistical calculations:
  - Mean
  - Median
  - Standard Deviation

### 6️⃣ Model Training & Testing
- Split data into training and testing sets
- Trained a **Logistic Regression** classification model
- Used cleaned and processed data for modeling

### 7️⃣ Model Evaluation
- Evaluated model performance using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

##  Results & Insights
- Petal features provide the best separation between iris species
- Data showed no missing or duplicate values after cleaning
- Mean and median values were close, indicating balanced distributions
- Logistic Regression achieved **high accuracy**, proving data quality
- Proper preprocessing significantly improves model performance

---

## Conclusion
This task successfully demonstrates the complete **data handling workflow**, including loading, inspection, cleaning, analysis, and basic modeling.  
The Iris dataset was effectively prepared using **NumPy and pandas**, and meaningful insights were gained through EDA and statistical analysis.  
This task builds a strong foundation for advanced machine learning and data science tasks.

---

##  Skills Gained
- NumPy array operations  
- pandas data manipulation  
- Data cleaning fundamentals  
- Exploratory Data Analysis (EDA)  
- Basic machine learning workflow
