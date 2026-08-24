# Student Habits & Exam Score Analysis

## 📌 Project Overview

This project analyzes the relationship between students' daily habits, lifestyle factors, and academic performance.

The analysis explores how factors such as study time, attendance, sleep, social media usage, exercise, and other lifestyle characteristics relate to students' exam scores.

## 🎯 Objectives

* Explore and understand the dataset.
* Clean and prepare the data for analysis.
* Analyze relationships between student habits and exam performance.
* Visualize important patterns and correlations.
* Prepare the data for machine learning.
* Build a Neural Network regression model to predict exam scores.

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras
* Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Inspection

* Dataset structure
* Data types
* Missing values
* Duplicate records
* Descriptive statistics

### 2. Data Cleaning

* Handling missing values
* Checking duplicate records
* Preparing categorical variables

### 3. Exploratory Data Analysis

The project uses different visualizations to investigate:

* Numerical feature distributions
* Categorical feature distributions
* Correlations between numerical variables
* Relationships between student habits and exam scores
* Exam score differences across categorical groups

### 4. Feature Engineering

Categorical variables are transformed into numerical features using one-hot encoding.

The dataset is then divided into:

* Features (`X`)
* Target variable (`exam_score`)

### 5. Machine Learning

A Neural Network regression model is trained using TensorFlow/Keras.

The model uses:

* ReLU activation functions
* Adam optimizer
* Mean Squared Error loss
* Training and validation data

### 6. Evaluation

The model performance is evaluated using:

* **R² Score**
* **RMSE (Root Mean Squared Error)**

## 📊 Results

The notebook contains the complete exploratory analysis, visualizations, model training, and evaluation results.

Model performance can be reproduced by running the notebook from start to finish.

## 📁 Repository Structure

```text
student-habits-exam-score-analysis/
│
├── student-habits-exam-score-analysis.ipynb
└── README.md
```

##  How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run the cells from top to bottom.

##  Author

**Saif Eldeen**

Data Engineering & Data Science Student
