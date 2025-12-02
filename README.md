Credit Card Fraud Detection

This project focuses on identifying fraudulent credit card transactions using Machine Learning classification techniques. The dataset contains anonymized numerical features derived through PCA along with a transaction amount column and a binary fraud label.

📌 Project Workflow
1. Data Preprocessing

Loaded and explored the credit card transactions dataset.

Handled class imbalance (fraud cases are extremely rare).

Scaled numerical features for improved model performance.

Split data into training and testing sets.

2. Exploratory Data Analysis (EDA)

Examined the distribution of legitimate and fraudulent transactions.

Visualized correlations between features and fraud labels.

Identified patterns in transaction amounts and time-based behavior.

Highlighted the extremely imbalanced nature of fraud datasets.

3. Modeling

Trained ML classification models (e.g., Logistic Regression, Random Forest, or other models used in your notebook).

Evaluated performance using:

Accuracy Score

Precision & Recall

F1 Score

Confusion Matrix

ROC–AUC Curve

Special focus on recall and precision, since in fraud detection, false negatives must be minimized.

🛠️ Tech Stack

Python

Pandas & NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

📊 Results

The model achieves strong performance in detecting fraudulent transactions while handling the highly imbalanced dataset. Using evaluation metrics such as recall and AUC, the project demonstrates the practical use of machine learning in financial fraud detection.
