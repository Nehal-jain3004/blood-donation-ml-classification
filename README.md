# 🩸 Blood Donation Classification using Machine Learning

Predicting whether a blood donor will donate again, and comparing multiple classification models using accuracy and cross-validation.

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)

## 📌 Overview
Blood banks need to forecast donor return rates to plan supply. This project builds and compares several classification models on the Blood Transfusion dataset to predict whether a donor will donate again.

## 📂 Dataset
- **File:** `blood.csv`
- **Size:** 748 donors
- **Features:** Recency (months since last donation), Frequency (total donations), Monetary (total blood donated, c.c.), Time (months since first donation)
- **Target:** Whether the donor donated in the target period (1 = yes, 0 = no)

## 🗂️ Repository Structure
```
├── Blood Donation Dataset.ipynb    # EDA and data preprocessing
├── Comparing Multiple Models.ipynb # Model training, evaluation, comparison
├── blood.csv                       # Dataset
└── README.md
```

## 🔬 Methodology
1. Data loading and exploration (distributions, class balance)
2. Preprocessing and train/test split
3. Training multiple models (e.g. Logistic Regression, Random Forest, KNN, SVM)
4. Evaluation using accuracy and k-fold cross-validation
5. Comparing models to pick the best performer

## 📊 Results
| Model | Accuracy | CV Score |
|-------|----------|----------|
| Logistic Regression | XX% | XX% |
| Random Forest | XX% | XX% |
| KNN | XX% | XX% |

**Best model:** _(name)_ with _(score)_

## 🚀 How to Run
```bash
git clone https://github.com/Nehal-jain3004/blood-donation-ml-classification.git
cd blood-donation-ml-classification
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook
```
Open `Blood Donation Dataset.ipynb` first, then `Comparing Multiple Models.ipynb`.

## 🛠️ Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

## 🔮 Future Improvements
- Hyperparameter tuning with GridSearchCV
- Handling class imbalance (SMOTE / class weights)
- Adding more evaluation metrics (precision, recall, ROC-AUC)

## 👤 Author
**Nehal Jain** · [GitHub](https://github.com/Nehal-jain3004)
