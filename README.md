# Iris Flower Classification using Logistic Regression  
A Machine Learning project that builds a Logistic Regression model to classify Iris flower species using four botanical measurements. This is a fundamental ML classification problem and a strong starting point for understanding supervised learning.

---

## 📌 Project Overview
The Iris dataset is a well-known multiclass classification dataset containing 150 samples across three species:
- Setosa  
- Versicolor  
- Virginica  

Each sample has:
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

The goal is to predict the correct species based on these features.


## 🧠 Objectives
- Understand how Logistic Regression works for multiclass classification (One-vs-Rest).
- Train, evaluate, and test a classification model.
- Learn how to measure accuracy and interpret model performance.


## 🛠️ Workflow

### **1. Data Loading**
Used `sklearn.datasets.load_iris()` to load the dataset.

### **2. Preprocessing**
- Extracted feature matrix **X**  
- Extracted label vector **y**

### **3. Train-Test Split**
Split the dataset into:
- **80% training data**
- **20% testing data**

### **4. Model Training**
Created and trained a Logistic Regression model using:
LogisticRegression(max_iter=200)

### **5. Prediction**
Predicted labels on the test data.

### **6. Evaluation**
Calculated accuracy using:
accuracy_score(y_test, y_pred)

 ## 📊 Results

Test Accuracy: 1.0
This high accuracy is expected due to the dataset’s simplicity and clear class separation.

### **How to Run the Project**
1. Install dependencies:
pip install -r requirements.txt

2. Run the script:
python iris_logistic.py


### **📚 What I Learned**


Logistic Regression for classification

Working with built-in datasets

Splitting data into train/test sets

Evaluating ML models using accuracy

Understanding multiclass classification



