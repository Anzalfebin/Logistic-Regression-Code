# Task 4: Classification with Logistic Regression

## 🎯 Project Objective
[cite_start]The goal of this project is to build a binary classifier using **Logistic Regression** to predict outcomes accurately based on provided features[cite: 3, 4]. [cite_start]This task involves the complete machine learning pipeline, including data preprocessing, feature standardization, model training, and performance evaluation[cite: 7, 10, 11].

## 🛠️ Tools & Technologies
* **Language:** Python
* [cite_start]**Libraries:** * `Scikit-learn`: For model implementation, scaling, and evaluation metrics[cite: 4].
    * [cite_start]`Pandas`: For data manipulation and loading[cite: 4].
    * [cite_start]`Matplotlib` & `Seaborn`: For generating performance visualizations like the Confusion Matrix and ROC Curve[cite: 4].

## 📊 Dataset
* [cite_start]**Source:** Breast Cancer Wisconsin Dataset (provided via Scikit-learn)[cite: 14].
* [cite_start]**Description:** A binary classification dataset used to distinguish between Malignant and Benign tumor samples[cite: 14].

## 🚀 Implementation Workflow
[cite_start]Following the internship's mini-guide, the project was executed in the following steps[cite: 7]:
1. [cite_start]**Data Preparation:** Loaded the dataset and split it into training and testing sets (70/30 split)[cite: 8, 9].
2. [cite_start]**Feature Scaling:** Applied `StandardScaler` to normalize the data, which is essential for the convergence of Logistic Regression[cite: 9].
3. [cite_start]**Model Training:** Initialized and trained the `LogisticRegression` model using the training data[cite: 10].
4. [cite_start]**Analysis:** Explored the **Sigmoid Function** and its role in mapping linear outputs to probabilities between 0 and 1[cite: 12, 16].



[Image of Sigmoid Function graph]


## 📈 Model Evaluation
[cite_start]To ensure the model's reliability, I evaluated it using the following metrics[cite: 11]:
* [cite_start]**Confusion Matrix:** To visualize correct and incorrect predictions for each class[cite: 11, 22].
* [cite_start]**Precision & Recall:** To measure the accuracy of positive predictions and the model's ability to find all positive instances[cite: 11, 20].
* [cite_start]**ROC-AUC:** To evaluate the model's performance across various classification thresholds[cite: 11, 21].



## 🧠 Key Learnings
* [cite_start]Understanding the difference between Linear and Logistic Regression[cite: 18].
* [cite_start]Implementing binary classification workflows[cite: 16].
* [cite_start]Handling class imbalances and choosing optimal classification thresholds[cite: 23, 24].

## 📂 Repository Structure
* `task_4_logic_regression.ipynb`: The main code for the task.
* `README.md`: Project documentation.
* `results/`: Contains saved plots of the Confusion Matrix and ROC Curve.

---
[cite_start]*Completed as part of the Elevate Labs AI & ML Internship.* [cite: 1, 2]d
