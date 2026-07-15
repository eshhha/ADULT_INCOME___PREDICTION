## Adult Income Dataset - Exploratory Data Analysis & Data Preprocessing

This project was completed as a group activity during the **Artificial Intelligence & Machine Learning Course at ICTAK Trivandrum**. The objective of this project is to understand the Adult Income Dataset through Exploratory Data Analysis (EDA) and perform comprehensive data preprocessing techniques to prepare the dataset for Machine Learning model development.

---

## Dataset Source

**Dataset Name:** Adult Income Dataset

**Source:** UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/2/adult

---

## Problem Statement

The objective of this dataset is to predict whether an individual's annual income exceeds **$50,000** based on demographic, educational, and occupational attributes.

Target Variable:

- Income
  - <=50K
  - >50K

---

## Dataset Understanding

Before preprocessing, the dataset was explored to understand its structure and quality.

The following analyses were performed:

- Loaded the dataset using Pandas.
- Displayed the first and last few records.
- Checked dataset dimensions.
- Inspected column names and data types.
- Generated statistical summaries.
- Identified numerical and categorical features.
- Examined the distribution of the target variable.
- Identified missing values.
- Detected duplicate records.
- Understood feature relationships.

---

## Exploratory Data Analysis (EDA)

The following visualizations were created to better understand the dataset.

### Numerical Feature Analysis

- Histogram
- Box Plot


Purpose:

- Understand data distribution
- Detect skewness
- Identify outliers

---


### Correlation Analysis

Correlation Heatmap was generated for numerical variables.

Purpose:

- Detect highly correlated features
- Understand feature relationships
- Reduce redundancy

---

########################################################################################################

# Data Preprocessing - Adult Income Dataset

The dataset was cleaned and transformed before applying Machine Learning algorithms.

The preprocessing steps include:

## 1. Missing Value Handling

Missing values were identified and handled appropriately.

Techniques used:

- Mode Imputation (Categorical Features)
- Median/Mean Imputation (Numerical Features)
- Verified that no missing values remained.

---

## 2. Duplicate Removal

Duplicate observations were detected and removed to improve data quality.

Steps:

- Checked duplicate records.
- Removed duplicate rows.
- Verified the updated dataset.

---

## 3. Data Cleaning

The following cleaning operations were performed:

- Removed unnecessary spaces.
- Standardized categorical values.
- Verified data types.
- Converted columns into appropriate formats.

---

########################################################################################################

# Outlier Handling - Adult Income Dataset

Outliers were detected primarily in numerical features.

The following procedure was followed:

- Identified outliers using **Box Plot**.
- Calculated the **Interquartile Range (IQR)**.
- Determined lower and upper boundaries.
- Applied IQR clipping to reduce the effect of extreme values.
  

Purpose:

- Improve model performance
- Reduce noise
- Preserve important observations

---

########################################################################################################

# Data Transformation - Adult Income Dataset

After cleaning, the dataset was transformed into a Machine Learning-ready format.

## Encoding

Categorical variables were converted into numerical values using:

- Label Encoding
- One-Hot Encoding
- Ordinal Encoding (where applicable)

Purpose:

- Enable Machine Learning algorithms to process categorical data.

---

## Feature Scaling

Numerical features were normalized using:

### Standard Scaling

Applied to:

- Normally distributed numerical features

Purpose:

- Standardize features with mean = 0 and standard deviation = 1.

---

### Min-Max Scaling

Applied where appropriate to transform values into the range:

0 → 1

Purpose:

- Improve convergence of distance-based algorithms.
- Ensure features have similar scales.

---

########################################################################################################


# Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
# Instructions to Run the Project

## Step 1

Clone the repository.

```bash
git clone https://github.com/your-username/Adult-Income-EDA.git
```

## Step 2

Navigate to the project folder.

```bash
cd Adult-Income-EDA
```

## Step 3

Install the required Python libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

or

```bash
pip install -r requirements.txt
```

## Step 4

Launch Jupyter Notebook.

```bash
jupyter notebook
```

## Step 5

Open the notebook:

```
Adult_Income_prediction(preprocessing).ipynb
```

Run all cells sequentially to reproduce the complete preprocessing workflow.

---

# Project Outcomes

By completing this project, we successfully:

✔ Understood the Adult Income Dataset

✔ Performed comprehensive Exploratory Data Analysis

✔ Cleaned the dataset

✔ Handled missing values

✔ Removed duplicate records

✔ Detected and treated outliers

✔ Encoded categorical features

✔ Scaled numerical variables

✔ Prepared the dataset for Machine Learning model development

---

# Future Scope

The preprocessed dataset can be used for building and evaluating Machine Learning classification models such as:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naïve Bayes
- Gradient Boosting
- XGBoost

Model performance can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

# Contributors

This project was collaboratively developed by:

- **Aleena Philip**
- **Esha Manohar**
- **Mohammed Naif**
- **Tojo Tom**

---

# License

This project is intended for educational and learning purposes under the ICTAK Data Science & Machine Learning Program.

---
