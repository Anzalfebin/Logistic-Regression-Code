Classification using Logistic Regression
This project demonstrates how to build a binary classification model using Logistic Regression.
The model is trained and evaluated using the Breast Cancer Wisconsin dataset available in scikit-learn.
🎯 Objective
Build a binary classifier using Logistic Regression
Perform data preprocessing and feature scaling
Evaluate the model using classification metrics
Understand threshold tuning and ROC curve
🛠 Tools & Libraries
Python
NumPy
Pandas
Matplotlib
Scikit-learn
📊 Dataset
The project uses the Breast Cancer Wisconsin dataset from sklearn.datasets.
This dataset contains:
569 samples
30 numerical features
Binary target:
0 → Malignant
1 → Benign
⚙️ Steps Performed
1. Data Loading
Loaded the dataset using sklearn's built-in dataset loader.
2. Train-Test Split
Split the dataset into:
80% training data
20% testing data
3. Feature Scaling
Standardized features using StandardScaler to improve model performance.
4. Model Training
Trained a Logistic Regression classifier using:
LogisticRegression() from sklearn
5. Predictions
Generated:
Class predictions
Probability scores
📈 Evaluation Metrics
Confusion Matrix
Shows:
True Positives
True Negatives
False Positives
False Negatives
Precision
Measures how many predicted positives were correct.
Recall
Measures how many actual positives were detected.
ROC-AUC Score
Measures model’s ability to distinguish between classes.
ROC Curve
Visual representation of classification performance across thresholds.
🎚 Threshold Tuning
A custom probability threshold was tested (e.g., 0.3 instead of default 0.5) to observe changes in model performance.
📂 Project Structure
Task4-Logistic-Regression/
│
├── task4.py
├── README.md
