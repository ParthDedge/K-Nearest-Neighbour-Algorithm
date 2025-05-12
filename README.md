# K-Nearest-Neighbour-Algorithm
# 📊 K-Nearest Neighbors (K-NN) on Social Network Ads Dataset

This repository demonstrates the implementation of the **K-Nearest Neighbors (K-NN)** algorithm, an intuitive and powerful classification technique, to predict user purchase behavior based on social network ad data.

---

## 🎯 Objective

To build a machine learning classification model using the **K-NN algorithm** that predicts whether a user is likely to purchase a product based on their features in a social network advertisement dataset.

We evaluate the model using:
- Confusion Matrix
- Accuracy
- Error Rate
- Precision
- Recall

---

## 📁 Dataset Overview

The dataset includes user data and whether they purchased a product after seeing an ad. Features typically include:
- Age
- Estimated Salary
- Purchased (target variable)

*Dataset Source:* Available [here](#) *(update this with the actual dataset link)*

---

## 🚀 Steps Followed

1. **Importing the Dataset**  
   - Load and explore the dataset using pandas.

2. **Preprocessing**  
   - Feature scaling using StandardScaler  
   - Splitting the dataset into training and test sets

3. **Model Training**  
   - Apply the K-NN classifier using `sklearn.neighbors.KNeighborsClassifier`

4. **Prediction and Evaluation**  
   - Generate predictions on the test set  
   - Evaluate using confusion matrix, accuracy, error rate, precision, and recall

---

## 📈 Model Evaluation

- **Confusion Matrix:** Understand how the model performs in classifying each category.
- **Accuracy:** Proportion of total predictions that were correct.
- **Error Rate:** Percentage of incorrect predictions.
- **Precision:** Fraction of relevant instances among the retrieved ones.
- **Recall:** Fraction of relevant instances that were retrieved.

This analysis provides a detailed view of the model's performance and reliability in predicting customer behavior.

---

## 🧰 Tools & Technologies Used

- **Python**
- **NumPy**, **Pandas**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 📂 Repository Contents

- `knn_social_network_ads.ipynb` – Jupyter notebook with full implementation
- `README.md` – Project documentation
