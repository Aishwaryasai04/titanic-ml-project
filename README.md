# titanic-ml-project
# 🛳️ Titanic Survival Prediction (Machine Learning Project)

This is a beginner-friendly machine learning project that predicts whether a passenger survived the Titanic disaster using Python and Logistic Regression. It is based on the popular Titanic dataset from Kaggle.

---

## 📌 Project Objective

Predict survival (`Survived` = 0 or 1) based on passenger information like:
- Age
- Sex
- Passenger class
- Fare
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Port of Embarkation

---

## 🔧 Tools & Libraries Used

- **Python**
- **pandas** – for data manipulation
- **matplotlib & seaborn** – for visualization
- **scikit-learn** – for model building and evaluation
- **Google Colab** – for code development

---

## 📊 Project Workflow

1. **Data Loading**
2. **Data Cleaning**
   - Dropped `Cabin` (too many missing values)
   - Filled `Age` with median and `Embarked` with mode
3. **Feature Engineering**
   - Converted `Sex` and `Embarked` to numeric values
   - Dropped irrelevant columns: `Name`, `Ticket`, `PassengerId`
4. **Train/Test Split**
   - 80% training / 20% testing
5. **Model Training**
   - Logistic Regression
6. **Model Evaluation**
   - Accuracy: **~80%**
   - Precision, Recall, F1-Score
   - Confusion Matrix

---

## ✅ Results

- **Final Accuracy:** 79.88%
- Model performs well on test data, especially for predicting non-survivors.
- Could be improved with advanced models (e.g., Random Forests or XGBoost).

---

## 📁 Files

| File                                | Description                             |
|-------------------------------------|-----------------------------------------|
| `titanic_survival_prediction.ipynb` | Jupyter notebook with full code         |
| `README.md`                         | Project overview and explanation        |

---

## 🔗 Dataset Source

- [Titanic: Machine Learning from Disaster (Kaggle)](https://www.kaggle.com/c/titanic)

---

## ✨ Author

**[Aishwarya Sai Yadav Bura]**  
[LinkedIn Profile](https://www.linkedin.com/in/-aishwaryasaibura/)  
[Portfolio Website](https://aishwaryasai04.github.io/aishwaryasai.github.io/index.html)

---

## 🏷️ Tags

`#MachineLearning` `#Python` `#TitanicDataset` `#LogisticRegression` `#DataScience` `#BeginnerProject`
