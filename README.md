# Task4
# Breast Cancer Classification using Logistic Regression

This project demonstrates a simple Logistic Regression model to classify tumors as **malignant** or **benign** using the Breast Cancer Wisconsin dataset.  
It includes data preprocessing, model training, evaluation, threshold tuning, and sigmoid function visualization.

## Project Structure

- `data.csv` → Dataset containing tumor features and diagnosis labels  
- `breast_cancer_classification.py` → Python code for building and evaluating the model  

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

## 📈 How it Works

### 1. Load Dataset  
Import and clean data from `data.csv`. Drop unused columns and encode the target label (`M` → 1, `B` → 0).

### 2. Preprocessing  
Standardize features using `StandardScaler`.

### 3. Train-Test Split  
Split the dataset into 80% training and 20% testing sets.

### 4. Model Training  
Train a `LogisticRegression` model using scikit-learn.

### 5. Prediction and Evaluation  
Predict tumor classes and evaluate the model using:

- Confusion Matrix  
- Precision, Recall, F1-Score  
- ROC-AUC Score  
- ROC Curve

### 6. Threshold Tuning  
Adjust the classification threshold (e.g., 0.3 instead of 0.5) to observe changes in precision and recall.

### 7. Sigmoid Visualization  
Plot the sigmoid function to explain how logistic regression maps inputs to probabilities.


