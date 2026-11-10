# 🌸 Task 1 – Iris Flower Classification

## 📌 Project Overview

This project is part of the **Datheon Machine Learning and Data Science Internship**.

The objective is to develop machine learning classification models to predict Iris flower species using the Iris dataset.

Two classification algorithms are implemented and compared:
- Logistic Regression
- Decision Tree Classifier

## 🎯 Objectives

- Explore and understand the Iris dataset.
- Perform Exploratory Data Analysis (EDA).
- Visualize feature distributions and correlations.
- Prepare data for machine learning.
- Train and evaluate classification models.
- Compare model performance using evaluation metrics.

## 📊 Dataset Description

**Dataset:** Iris Dataset (loaded using Scikit-learn)

The dataset contains:
- 150 observations
- 4 numerical features
- 3 target classes

### Features

1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)

### Target Classes

- Setosa
- Versicolor
- Virginica

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Project Workflow

1. Import required libraries.
2. Load the Iris dataset.
3. Perform data exploration.
4. Check missing values and statistical summaries.
5. Perform Exploratory Data Analysis.
6. Generate correlation heatmap and pairplot.
7. Separate features and target variables.
8. Split data into training and testing sets.
9. Apply feature scaling.
10. Train Logistic Regression.
11. Train Decision Tree Classifier.
12. Evaluate and compare both models.

## 📈 Exploratory Data Analysis

### Correlation Heatmap

![Correlation Heatmap]([correlation_heatmap.png](https://github.com/prasanth491999-prog/Datheon_Machine_Learning_and_Data_Science_Internship/blob/main/Task_1_Classification/Images/correlation_heatmap.png))

### Species Distribution

![Species Distribution](images/species_distribution.png)

### Pairplot

![Pairplot](images/pairplot.png)

## 🤖 Machine Learning Models

### 1. Logistic Regression

A supervised classification algorithm used to predict the Iris flower species.

### 2. Decision Tree Classifier

A tree-based supervised learning algorithm used for multiclass classification.

## 📊 Model Performance

Both models were evaluated using a 20% testing dataset.

| Model | Accuracy |
|---|---:|
| Logistic Regression | 93.33% |
| Decision Tree | 93.33% |

### Confusion Matrices

**Logistic Regression**

![Logistic Regression Confusion Matrix](images/logistic_regression_confusion_matrix.png)

**Decision Tree**

![Decision Tree Confusion Matrix](images/decision_tree_confusion_matrix.png)

## 📉 Decision Boundary Visualization

**Logistic Regression**

![Logistic Regression Boundary](images/logistic_regression_boundary.png)

**Decision Tree**

![Decision Tree Boundary](images/decision_tree_boundary.png)

## 🏆 Conclusion

Both Logistic Regression and Decision Tree achieved an accuracy of 93.33% on the test dataset.

The project demonstrates the implementation of a complete classification workflow, including data exploration, preprocessing, model training, evaluation and visualization.

## 📁 Project Files

- `classification_pipeline.ipynb` – Complete Python implementation.
- `Dataset/` – Dataset-related files.
- `images/` – Project visualizations.
- `requirements.txt` – Required Python libraries.

## 👨‍💻 Internship

**Organization:** Datheon  
**Program:** Machine Learning and Data Science Internship  
**Task:** Task 1 – Classification

---
