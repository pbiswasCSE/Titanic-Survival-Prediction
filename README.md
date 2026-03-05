# Titanic Survival Prediction (Kaggle)

This repository contains my solution for the world-famous **Kaggle Titanic competition**. This is my first machine learning project, where I achieved a solid score by predicting which passengers survived the shipwreck.

##  Project Achievement
- **Kaggle Public Score:** 0.78468
- **Local Validation Accuracy:** ~82.27%
- **Ranking:** Successfully placed in a competitive position on the global leaderboard.

##  Overview
The goal of this project is to apply machine learning tools to predict which passengers survived the Titanic tragedy based on features like age, gender, ticket class, and more.

##  Key Steps Taken

### 1. Data Cleaning & Preprocessing
- Handled **Missing Values**: Imputed missing `Age` with the median and `Embarked` with the mode.
- **Feature Dropping**: Removed the `Cabin` column due to too many missing values.

### 2. Feature Engineering
- **Title Extraction**: Extracted titles (Mr, Mrs, Miss, Master, etc.) from passenger names to better predict survival patterns.
- **Family Analysis**: Created a `FamilySize` feature to see if traveling alone or with family affected survival chances.

### 3. Model Building
- **Algorithm:** Random Forest Classifier.
- **Tools:** Python, Pandas, Scikit-learn.
- **Validation:** Used Cross-Validation to ensure the model doesn't overfit and performs well on new data.

## Repository Structure
- `titanic-survival.ipynb`: The main Jupyter Notebook with all data analysis and model code.
- `submission.csv`: The final prediction file submitted to Kaggle.

##  How to use
1. Clone this repository.
2. Ensure you have `pandas`, `numpy`, and `scikit-learn` installed.
3. Run the notebook using Kaggle or Jupyter Notebook.


