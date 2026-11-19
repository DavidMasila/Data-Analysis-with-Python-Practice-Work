# Data Analysis with Python: Practice Work

This folder holds my hands-on practice from two learning sources:

- **IBM Skills Network**: Data Analysis with Python
- **Kaggle Learn**: data cleaning, data visualization and pandas micro-courses

Together they cover the full workflow: loading and cleaning data, exploring it, testing relationships, and building and evaluating regression models.

## Skills Practiced

**Data cleaning and wrangling** (IBM + Kaggle Learn)
- Handling missing values, duplicates and incorrect data types
- Standardizing and normalizing data, binning, and creating indicator (dummy) variables
- Fuzzy matching for messy text fields

**Exploratory analysis and statistics** (IBM)
- Descriptive statistics and grouping/aggregation with pandas
- Pearson correlation (coefficient and p-value)
- ANOVA for comparing group means

**Data visualization** (IBM + Kaggle Learn)
- Plots for distributions, relationships and comparisons across categories

**Model development** (IBM)
- Simple Linear Regression (SLR)
- Multiple Linear Regression (MLR)
- Polynomial regression
- Pipelines to chain preprocessing and modeling steps

**Model evaluation and refinement** (IBM)
- Train/test splits
- Cross-validation
- Overfitting and underfitting
- Ridge regression and regularization

## Notebooks

| Notebook | Focus | Source |
|---|---|---|
| `PandasIntro.ipynb` | pandas basics | Kaggle Learn |
| `datacleaning.ipynb` | Cleaning raw data | Kaggle Learn |
| `fuzzy.ipynb` | Fuzzy matching | Kaggle Learn |
| `data_visualization.ipynb` | Visualization | Kaggle Learn |
| `Data Wrangling1.ipynb` | Data wrangling, part 1 | IBM |
| `Data_Wrangling2.ipynb` | Data wrangling, part 2 | IBM |
| `model_development.ipynb` | SLR, MLR, polynomial regression, pipelines | IBM |
| `model_evaluation.ipynb` | Cross-validation, ridge regression | IBM |

## Datasets

CSV files used across the notebooks:

`auto.csv`, `automobiles.csv`, `automobiles_clean_df.csv`, `module_5_auto.csv`, `Building_Permits.csv`, `Museum_Visitors.csv`, `NFL Play by Play 2009-2017 (v4).csv`, `cancer.csv`, `candy.csv`, `catalog.csv`, `database.csv`, `fifa.csv`, `flight_delays.csv`, `ign_scores.csv`, `insurance.csv`, `iris.csv`, `ks-projects-201612.csv`, `ks-projects-201801.csv`, `pakistan_intellectual_capital.csv`, `spotify.csv`

## Tools

- Python 3
- pandas, NumPy
- Matplotlib, seaborn
- SciPy (statistical tests)
- scikit-learn (regression, pipelines, cross-validation, ridge)
- Jupyter Notebook

## Setup

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
jupyter notebook
```

Open any notebook from the table above. Keep the CSV files in this same folder so the relative paths work.

## Sources

- IBM Skills Network: Data Analysis with Python
- Kaggle Learn: Data Cleaning, Data Visualization and Pandas courses
