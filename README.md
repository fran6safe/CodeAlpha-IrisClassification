# 🌸 Iris Flower Classification – CodeAlpha Internship Task 1

This project was done as part of my **Data Science Internship at CodeAlpha**.

## 📊 Project Description
The Iris dataset contains 150 samples of flowers with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

The goal is to classify the flower into one of three species:
- Setosa
- Versicolor
- Virginica

## 🧠 Approach
1. Data exploration & visualization (pairplots, correlations)
2. Data preprocessing:
   - Label encoding of species
   - Train-test split (80/20)
   - Feature scaling using StandardScaler
3. Model training:
   - Logistic Regression
   - Random Forest
4. Model evaluation:
   - Accuracy score: **93.3%**
   - Confusion matrix & classification report
5. Model saving (joblib)

## 🛠 Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
