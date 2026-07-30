# Adult Income Prediction using Machine Learning

##  Project Overview

This project aims to predict whether an individual's annual income exceeds **$50K** using demographic and employment-related information from the Adult Census Income dataset.

The project covers the complete machine learning workflow, including:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Model building
- Hyperparameter tuning
- Model validation
- Ensemble learning
- Performance evaluation

The objective is to compare multiple machine learning algorithms and identify the best-performing model for income classification.

---

# Dataset Information

- **Dataset Name:** Adult Census Income Dataset
- **Source:** UCI Machine Learning Repository
- **Dataset Link:**
  https://archive.ics.uci.edu/dataset/2/adult

### Target Variable

- **income**
  - <=50K
  - >50K

---

# Exploratory Data Analysis (EDA)

The following analyses were performed before model building:

- Dataset inspection
- Shape of dataset
- Data types
- Missing value analysis
- Duplicate record analysis
- Statistical summary
- Distribution plots
- Count plots
- Correlation heatmap
- Outlier detection
- Feature relationship analysis

---

# Data Preprocessing

The following preprocessing steps were carried out:

### 1. Missing Value Handling

- Identified missing values
- Replaced missing categorical values where necessary

### 2. Duplicate Removal

- Checked and removed duplicate records

### 3. Outlier Handling

- Detected outliers using statistical methods
- Removed or treated extreme values where applicable

### 4. Encoding

Categorical features were converted into numerical format using:

- Label Encoding
- One-Hot Encoding
- Ordinal Encoding

### 5. Feature Scaling

Numerical features were standardized using:

- StandardScaler

### 6. Train-Test Split

Dataset split into:

- Training set
- Testing set

---

# Machine Learning Models

The following machine learning algorithms were implemented.

| Model | Description |
|--------|-------------|
| Logistic Regression | Linear classification model |
| Decision Tree | Tree-based classifier |
| K-Nearest Neighbors (KNN) | Distance-based classifier |
| Support Vector Machine (SVM) | Margin-based classifier |
| Gaussian Naive Bayes | Probabilistic classifier |
| Gradient Boosting | Boosting ensemble model |
| AdaBoost | Adaptive boosting classifier |
| Artificial Neural Network (ANN) | Deep learning model |

---

# Team Member Contributions

| Team Member | Models Implemented |
|-------------|-------------------|
| **Esha Manohar** | Exploratory Data Analysis (EDA), Logistic Regression, Stacking |
| **Muhammed Naif** | Data Preprocessing, K-Nearest Neighbors (KNN), Gradient Boosting |
| **Aleena Philip** | Feature Scaling, Decision Tree, Bagging |
| **Tojo Tom** | Encoding, Support Vector Machine (SVM), AdaBoost, Naive Bayes,Bagging |


---

# Validation Techniques

To ensure reliable model performance, the following validation techniques were used:

- Train-Test Split
- Stratified K-Fold Cross Validation
- Cross Validation Score

These techniques reduce bias and provide a better estimate of model performance on unseen data.

---

# Hyperparameter Tuning

Hyperparameter optimization was performed using:

- GridSearchCV
- RandomizedSearchCV

Parameters tuned include:

- Number of neighbors (KNN)
- Maximum depth (Decision Tree)
- Regularization parameter C (Logistic Regression)
- Kernel type (SVM)
- Number of estimators (Boosting models)
- Learning rate
- Tree depth
- Smoothing parameter (Naive Bayes)

---

# Ensemble Models

The project includes the following ensemble learning techniques.

## Bagging

- Base Estimator: Decision Tree
- Multiple trees trained on random subsets
- Final prediction through majority voting

## Gradient Boosting

- Sequential boosting approach
- Each model corrects previous model errors

## AdaBoost

- Adaptive boosting classifier
- Focuses on misclassified samples

## Stacking

Base Models:

- K-Nearest Neighbors
- Decision Tree

Meta Model:

- Logistic Regression

---

# Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Cross Validation Score

These metrics help compare the classification performance of different algorithms.

---

# Results

After training and evaluation:

- Multiple classification models were compared.
- Hyperparameter tuning improved overall model performance.
- Ensemble learning methods generally achieved better predictive performance than individual models.
- Stacking and boosting models demonstrated competitive results on the Adult Income dataset.

> You can include a table of final accuracies here after running all models.

Example:

| Model | Accuracy |
|---------|----------|
| Logistic Regression | 0.8449 |
| Decision Tree | 0.8197 |
| KNN | 0.8290 |
| SVM | 0.8486 |
| Naive Bayes | 0.7554 |
| Gradient Boosting | 0.8633 |
| AdaBoost | 0.8501 |
| Bagging | 0.8554 |
| Stacking | 0.8515 |
| ANN | 0.8516 |

---

# Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

---

# How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/Adult_Income_Prediction.git
```

### Navigate to the project directory

```bash
cd Adult_Income_Prediction
```

### Install required libraries

```bash
pip install -r requirements.txt
```

### Open the notebook

Launch Jupyter Notebook or Google Colab and open:

```
Adult_Income_prediction(preprocessing).ipynb
```

### Run all cells sequentially

The notebook performs:

1. Data loading
2. EDA
3. Preprocessing
4. Feature engineering
5. Model training
6. Hyperparameter tuning
7. Ensemble learning
8. Model evaluation

---

# Project Structure

```
Adult_Income_Prediction/
│
├── Adult_Income_prediction.ipynb
├── adult.csv
├── README.md
├── requirements.txt
└── images/
```

---

# References

- UCI Machine Learning Repository
- Scikit-learn Documentation
- TensorFlow Documentation
- Pandas Documentation

---

# License

This project is developed for educational and academic purposes.

---

# Acknowledgements

We thank the UCI Machine Learning Repository for providing the Adult Census Income dataset and the open-source Python community for the machine learning libraries used in this project.


