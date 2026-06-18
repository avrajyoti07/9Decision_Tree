# 🌳 Salary Prediction — Decision Tree Classifier

A machine learning project that predicts whether an employee earns **more than $100K** based on their **company**, **job role**, and **degree**, using a Decision Tree Classifier.

## 📌 What It Does
- Loads a salary dataset with `company`, `job`, `degree`, and `salary_more_than_100k` columns
- Encodes categorical features using `LabelEncoder`
- Trains a **Decision Tree Classifier** using scikit-learn
- Achieves **90% accuracy** on the dataset
- Predicts salary class for any new employee profile

## 🔍 Sample Prediction
```python
model.predict([[2, 0, 1]])  # → [1]  (salary > 100k)
```

## 📊 Model Performance
| Metric | Score |
|--------|-------|
| Accuracy | **0.9 (90%)** |

## 🚀 Run It
```bash
pip install pandas scikit-learn
jupyter notebook 8Decision_Tree.ipynb
```

## 🛠️ Built With
Python · Pandas · Scikit-learn · Jupyter Notebook
