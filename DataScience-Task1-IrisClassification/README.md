
# 🌸 Iris Flower Classification

**Oasis Infobyte SIP — Data Science Track — Task 1**

## Objective
Train a machine learning classification model to identify the species of an iris flower
(*Setosa*, *Versicolor*, or *Virginica*) based on four physical measurements: sepal length,
sepal width, petal length, and petal width.

## Tech Stack
- Python
- pandas
- scikit-learn
- matplotlib / seaborn
- Jupyter Notebook

## Dataset
The classic Iris dataset, loaded directly from `sklearn.datasets.load_iris()` — no external
download required. 150 samples, 3 balanced classes (50 samples each).

## What's Inside
- `Iris_Flower_Classification.ipynb` — full notebook covering:
  - Exploratory Data Analysis (shape, dtypes, nulls, descriptive stats)
  - Visualizations: pairplot, box plots per feature, correlation heatmap
  - Feature selection discussion
  - Train/test split (80/20, stratified)
  - Two required models: **Logistic Regression** and **K-Nearest Neighbors**
  - Bonus model: **Decision Tree**
  - Evaluation: accuracy, confusion matrix, classification report (precision/recall/F1) for each model
  - Model comparison table and chart
  - Conclusion identifying the best-performing model

## Key Findings
- Petal length and petal width are the most discriminative features for species classification.
- *Setosa* is linearly separable from the other two species.
- The main classification challenge is distinguishing *Versicolor* from *Virginica*, due to slight
  overlap in their petal measurements.

## How to Run
1. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
2. Open the notebook: `jupyter notebook Iris_Flower_Classification.ipynb`
3. Run all cells top to bottom.

---
*Part of the [OIBSIP](../) internship submission repository.*
