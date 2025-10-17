# 📊 Bank Customer Loan Approval Prediction 

## 📘 Project Overview
The **Bank Customer Loan Approval Prediction** project focuses on analyzing and predicting customer eligibility — i.e., whether a customer is eligibal to take loan or  not.

The dataset contains information on **5000 customers** from a Bank.  
Each record represents one customer and includes details about their **'ID','Age', 'Experience', 'Income', 'ZIP.Code', 'Family', 'CCAvg',
       'Education', 'Mortgage', 'Personal.Loan', 'Securities.Account',
       'CD.Account', 'Online', 'CreditCard'** .

---

## 🎯 Aim
To **predict whether a customer will take loan or not** using machine learning techniques.

---

## 🧠 Libraries Used

The following essential libraries were utilized for data manipulation, visualization, model building, and evaluation:

* **`numpy`**: Fundamental package for scientific computing and array operations.
* **`pandas`**: For data manipulation and analysis.
* **`seaborn`** & **`matplotlib.pyplot`**: For Exploratory Data Analysis (EDA) and visualization.
* **`sklearn.model_selection.train_test_split`**: To split the dataset into training and testing sets.
* **`sklearn.tree.DecisionTreeClassifier`**, **`plot_tree`**, **`export_text`**: For model training and visualization of the resulting decision tree.
* **`sklearn.metrics.ConfusionMatrixDisplay`** & **`score`**: For model performance evaluation.

---

## 🛠️ Project Workflow

The project followed a systematic approach to model development:

1.  **Data Import and Initial Assessment**: Loading the dataset and examining its structure.
2.  **Exploratory Data Analysis (EDA)**: Identifying patterns, checking for missing values, and visualizing key feature distributions.
3.  **Data Splitting**: Dividing the cleaned data into training and testing sets.
4.  **Model Training**: Fitting the **Decision Tree Classifier** to the training data.
6.  **Feature Importance and Optimization**: Analyzing feature contributions and considering potential model traing
7.  **Removing overfitting using max_depth**:Analyzing train and test accuracy with respect to max_depth ; optimizing it.
8.  **Removing overfitting using min_sample_split**: Analyzing train and test accuracy with respect to min_sample_split ; optimizing it.
9.  **Model Evaluation**: Assessing performance using metrics like **accuracy score** and displaying the **confusion matrix**.


---
## Test Score
98%

---
## ⚙️ Model and Algorithm

### **Algorithm Used: Decision Tree Classifier** 🌳

* The machine learning model chosen for this prediction task is the **Decision Tree Classifier** from `scikit-learn`.
* The model is trained based on the **entropy** criterion, which measures the impurity or randomness of the data to guide the optimal splitting of nodes in the tree. This helps in building a tree that provides the most information gain at each split, leading to better classification of churn and non-churn customers.

---
## Links
**[check out on kaggle]-->(https://www.kaggle.com/code/shreyanshkandu/bank-customer-loan-approval)**
