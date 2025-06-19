# heart-failure-prediction-models
A machine learning project using regression and classification models to analyze and predict outcomes related to heart failure based on clinical records.

# Heart Failure Prediction Using Machine Learning

This project applies regression and classification machine learning models to predict mortality and severity in patients with heart failure. Using clinical features from a publicly available dataset, the notebook performs exploratory data analysis, builds multiple predictive models, and evaluates their performance.

## 📊 Dataset

The dataset used is: `heart_failure_clinical_records_with_severity.csv`, which contains medical records of heart failure patients, including various health indicators and outcome variables (`DEATH_EVENT`, `Severity`).

## 🚀 Features & Workflow

### 1. Exploratory Data Analysis (EDA)
- Histogram and boxplot visualizations
- Heatmap of feature correlations
- Pairplots by death event status

### 2. Regression Modeling (Predicting Severity)
- Linear Regression
- Ridge & Lasso Regression
- Custom Kernel Regression (Linear, Polynomial, RBF)
- Support Vector Regression (SVR) for kernel comparison

### 3. Classification Modeling (Predicting DEATH_EVENT)
- Logistic Regression
- Naive Bayes
- Random Forest
- Support Vector Machines (SVM) with various kernels

### 4. Evaluation Metrics
- Mean Squared Error (for regression tasks)
- Accuracy, Precision, Recall (for classification tasks)

## 🧠 Key Findings

- Ridge and Linear regression performed similarly on severity prediction.
- Polynomial kernel regression (degree = 2) gave the best result among kernel methods.
- Random Forest achieved the highest accuracy (91%) in predicting mortality.
- SVM with a linear kernel had strong recall performance.

## 📁 Folder Structure

