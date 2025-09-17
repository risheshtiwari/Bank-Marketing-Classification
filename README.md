**Project Title: Bank Marketing Classification**

**📄 Overview**

This project focuses on building a machine learning model to predict whether a customer will subscribe to a term deposit based on the **Bank Marketing UCI dataset**. The main challenge addressed is the **class imbalance** in the dataset, where a vast majority of customers did not subscribe. To overcome this, the **SMOTE (Synthetic Minority Over-sampling Technique)** method was implemented to improve model performance.

**💾 Dataset**

The dataset used is the **Bank Marketing UCI dataset**, available from the UCI Machine Learning Repository. It contains data from direct marketing campaigns conducted by a Portuguese banking institution.
- **Source:** https://archive.ics.uci.edu/ml/datasets/bank+marketing
- **File Name:** bank-full.csv
- **Features:** It includes customer attributes such as age, job, marital status, and loan history, along with campaign-related information.
- **Target Variable:** The variable y indicates whether the customer subscribed to a term deposit (yes or no).

**🛠️ Methods and Libraries**

- **Preprocessing:** pandas for data manipulation, scikit-learn for data splitting, scaling (StandardScaler), and encoding (OneHotEncoder).
- **Handling Imbalance:** imblearn (Imbalanced-learn) for applying SMOTE.
- **Model Building:** scikit-learn for implementing Logistic Regression and K-Nearest Neighbors (KNN).
- **Hyperparameter Tuning:** GridSearchCV for finding optimal model parameters.
- **Evaluation:** scikit-learn.metrics for accuracy, classification_report, confusion_matrix, and ROC curve.
- **Visualization:** matplotlib and seaborn for creating plots (e.g., confusion matrices, ROC curve).

**📋 Instructions**

1. **Clone the Repository:** If your code is on GitHub, provide the clone command:
git clone <repository_url>
2. **Install Dependencies:** Make sure you have all the necessary libraries installed. You can use pip:
pip install pandas scikit-learn matplotlib seaborn imbalanced-learn
3. **Place the Dataset:** Download the bank-full.csv file and place it in the same directory as the Python script (.py file).
4. **Run the Script:** Execute the Python script from your terminal:
python your_script_name.py

**📈 Results**

The analysis compared two models: Logistic Regression and KNN. Both models were trained using SMOTE to handle the imbalanced dataset.

- **Logistic Regression:** Achieved an accuracy of approximately **84.0%**.
- **K-Nearest Neighbors (KNN):** Achieved a slightly higher accuracy of approximately **85.0%**.

While KNN had higher accuracy, Logistic Regression showed a slightly better **AUC score**, indicating its superior ability to distinguish between positive and negative classes.

[Final Project Report](report.pdf)

**✒️ Author**

- **Name:** Rishesh Tiwari
- **Student ID:** 2511MC03





