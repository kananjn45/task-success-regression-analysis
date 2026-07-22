# AI Engineer Regression

Regression analysis on an AI Engineer productivity dataset, predicting **Task_Success_Rate** from behavioral and cognitive features (AI usage, sleep, stress, cognitive load, coffee intake, etc.).

## What's inside

- **Data exploration**: shape, info, describe, null/duplicate checks
- **Cleaning**: dropped irrelevant columns (`Hours_Coding`, `Lines_of_Code`, `Bugs_Found`, etc.)
- **Visualization**: scatterplots, boxplots, regression plots, and a correlation heatmap (seaborn/matplotlib)
- **Modeling**: six regression models compared on the same train/test split:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - SVR
  - K-Neighbors Regressor
- **Evaluation**: R² scores compared across models with a horizontal bar chart

## Files

- `AI-Engineer-Regression.ipynb` — main notebook
- `AI-Engineer-Regression.csv` — dataset (add this file to the repo alongside the notebook, or update the read path if hosting the CSV elsewhere)

## Requirements

```
pandas
matplotlib
seaborn
scikit-learn
```

## Usage

Open the notebook in Jupyter and run cells top to bottom. Make sure `AI-Engineer-Regression.csv` is in the same directory.
