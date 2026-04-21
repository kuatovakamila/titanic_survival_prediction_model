# Titanic Survival Prediction Model

> A machine learning project that predicts passenger survival on the Titanic using binary classification.

📓 **Notebook:** [`titanic_model.ipynb`](./titanic_model.ipynb)

---

## Overview

This project applies supervised machine learning to the iconic Titanic dataset to predict whether a given passenger survived the disaster. It walks through the full data science pipeline — from raw data exploration and cleaning to model training, evaluation, and interpretation.

---

## Pipeline

### 🔍 Exploratory Data Analysis (EDA)
Understanding the dataset through statistical summaries and visualizations — uncovering patterns across features like passenger class, age, sex, and fare.

### 🧹 Data Preprocessing
Handling missing values, encoding categorical variables (e.g. `Sex`, `Embarked`), and engineering features to prepare clean input for the model.

### 🤖 Model Training
Training a binary classification model to predict survival (`0 = Did not survive`, `1 = Survived`) using labeled passenger records.

### 📊 Evaluation
Assessing model performance with metrics including accuracy, precision, recall, and a confusion matrix.

---

## Dataset Features

| Feature | Description |
|---------|-------------|
| `Pclass` | Passenger class (1st, 2nd, 3rd) |
| `Sex` | Gender of the passenger |
| `Age` | Age in years |
| `SibSp` | Number of siblings / spouses aboard |
| `Parch` | Number of parents / children aboard |
| `Fare` | Passenger fare |
| `Embarked` | Port of embarkation (C, Q, S) |
| `Survived` | Target variable — 0 or 1 |

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | Model training & evaluation |
| Jupyter Notebook | Interactive development |

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/kuatovakamila/titanic_survival_prediction_model.git
cd titanic_survival_prediction_model

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch the notebook
jupyter notebook titanic_model.ipynb
```

---

## Dataset Source

The Titanic dataset is sourced from the [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic) — one of the most well-known introductory datasets in machine learning.

---

## License

This project is open source and available under the [MIT License](LICENSE).
