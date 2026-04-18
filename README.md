# Palmer Penguins Species Classification

A machine learning group project classifying penguin species using physical measurements from the Palmer Penguin Dataset by Allison Horst, Alison Hill, and Kristen Gorman.

*Project Collaborators: Liran Zhang & Ryan Vock*

## Project Overview

Using the Palmer Penguins dataset, this project applies exploratory data analysis
and automated feature selection to identify the best predictors of penguin species,
then compares three classification models.

## Files

| File | Description |
|------|-------------|
| `Penguin_Classification.ipynb` | Full notebook: EDA, feature selection, model training & evaluation |
| `Penguin_Project_Report.pdf` | Exported notebook with all outputs and analysis |

## Approach

1. **Exploratory Analysis** — Summary statistics and visualizations (scatter plots,
   box plots, bar charts) to identify patterns across species and islands
2. **Automated Feature Selection** — Cross-validation across all feature combinations
   to find the optimal 3 features: Sex, Culmen Length, Culmen Depth
3. **Model Comparison** — Three classifiers evaluated with cross-validation and
   confusion matrices

## Results

| Model | Test Accuracy |
|-------|--------------|
| Extra Trees Classifier | 98.4% |
| Random Forest Classifier ⭐ | 98.4% |
| K Neighbors Classifier | 95.2% |

**Best model: Random Forest Classifier** (depth=4) — tied for highest accuracy
with a simpler, more efficient structure than ETC.

## Tech Stack

Python, scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
