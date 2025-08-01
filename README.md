# 🌸 Iris Flower Classification

A simple Machine Learning project that classifies iris flowers into **Setosa**, **Versicolor**, or **Virginica** based on the dimensions of their petals and sepals.

---

## 📘 Project Overview

This project uses the **Iris dataset**, one of the most famous datasets in pattern recognition, to build a model that can predict the species of an iris flower using:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 📊 Dataset Information

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- **Classes**: Setosa, Versicolor, Virginica
- **Samples**: 150
- **Features**:
  - sepal length (cm)
  - sepal width (cm)
  - petal length (cm)
  - petal width (cm)

---

## 🔧 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

## 📈 Workflow

1. **Data Loading**  
   Loaded the Iris dataset using `sklearn.datasets`.

2. **Exploratory Data Analysis (EDA)**  
   - Displayed data shape and column names  
   - Used seaborn & matplotlib to visualize feature relationships  
   - Pairplots, histograms, and boxplots

3. **Data Preprocessing**  
   - Checked for null values  
   - Encoded target labels

4. **Model Building**  
   - Split data using `train_test_split`  
   - Trained models:  
     - Logistic Regression  
     - K-Nearest Neighbors (KNN)  
     - Support Vector Machine (SVM)  
     - Decision Tree  
     - Random Forest

5. **Model Evaluation**  
   - Accuracy scores calculated  
   - Confusion matrix and classification report used  
   - Best accuracy achieved: **93.33%** (fill in your top result)
