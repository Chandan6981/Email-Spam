# 📧 Email Spam Detection Project

This project uses machine learning models to classify email messages as **spam** or **ham** (not spam). The classification is based on the text content of the emails using NLP techniques and supervised learning algorithms.

---

## 🔍 Problem Statement

With the increase in digital communication, spam emails have become a major issue. This project aims to build a reliable spam detection system that can automatically classify emails using machine learning models.

---

## 📁 Dataset

The dataset used is `spam.csv`, which contains the following columns:

- `Category`: Label (`ham` or `spam`)
- `Message`: The email content

**Make sure** to place the `spam.csv` file in the same directory as the Python script or Jupyter notebook.

---

## 🧰 Technologies Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Natural Language Processing (NLP)

---

## ⚙️ Models Implemented

1. **Decision Tree Classifier**
2. **Gaussian Naive Bayes**
3. **Multinomial Naive Bayes**

Each model is evaluated using:
- Accuracy Score
- Confusion Matrix

---

## 📈 Results

A bar graph is generated to compare the accuracy of all three models, and the best-performing model is printed at the end.

---

## 🛠 How to Run

1. Clone the repository or download the project folder.
2. Install required libraries (if not already installed):
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
