# cycle1

---

## Daily Progress

| Day   | Task Summary |
|-------|--------------|
| **Day 1** | Performed EDA by cleaning the dataset (handling missing values and outliers) and visualizing key relationships (e.g., stress vs sleep, mental health vs burnout) to uncover early signs of burnout. |
| **Day 2** | Perform regression using engineered features: encode categorical data, normalize numerics, select key features via correlation/mutual info, create 2 interactions, train Linear/Ridge/Lasso models on Stress_level, and compare using MSE and R². |
| **Day 3** | Trained Logistic Regression and LDA models for burnout prediction, evaluate using Accuracy, Confusion Matrix, and ROC-AUC (with ROC plot), and compare model performance. |
| **Day 4** | Train Decision Tree, Random Forest, and k-NN classifiers, identify and drop weak features using correlation, mutual info, or feature importance, then retrain models and compare performance before vs after feature selection.|
| **Day 5** | Cleaned and preprocessed the messy dataset, selected optimal features, and trained a regression model to boost R² from < 0.6 to > 0.85.

---

## Repository Contents

- `Day_01_Burnout_Breakdown.ipynb`               – Data cleaning and EDA
- `Day_02_Burnout_Breakdown.ipynb`               – Feature encoding and preprocessing
- `Day_03_Burnout_Breakdown.ipynb`               – Logistic Regression, Linear discriminant analysis and Classification metrics: Accuracy, ROC-AUC 
- `Day_04_Burnout_Breakdown.ipynb`               – Decision Trees (structure, criteria), Random Forests (feature importance, hyperparams) and k-NN
- `Main_Challenge_Dirty_Dataset_Detective.ipynb` – Data cleaning, EDA, Feature Selection, Regression modeland R^2 
---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization, where applicable)
- Warnings 
- Seaborn

