# Nutritional Data Analysis

**OpenClassrooms — Data Scientist Path | Project 3** (October–December 2022)

> Note: project deliverables (notebooks, presentation) are in French.

## Sector
Health

## Tech Stack
- Jupyter Notebook
- Python: pandas, numpy, matplotlib, seaborn, scikit-learn (kNN, GridSearchCV)

## Keywords
statistical testing, exploratory analysis, data cleaning, bag-of-words

## Context
Santé Publique France (the French public health agency) launched an open call for projects around food-related health issues, seeking innovative app ideas to help improve the eating habits of the French population.

## Mission
Propose an app concept and conduct an exploratory analysis to verify that the idea is feasible using the nutritional dataset provided.

**App concept:** the user scans a product barcode; the app suggests alternatives from the same food category with the best possible nutritional value and the lowest degree of processing.

## Deliverables
- `notebook_nettoyage.ipynb` — data cleaning notebook
- `notebook_exploration.ipynb` — exploratory analysis notebook (univariate and multivariate)
- `presentation.pdf` — presentation slides (in French)

## Methodology

1. **Data cleaning**
   - Select relevant variables
   - Handle duplicates (keep the entry with fewest missing values and most recent update)
   - Handle outliers (removal or mean imputation)
   - Handle missing values (zero-fill, mean imputation, kNN estimation)

2. **Exploratory analysis**
   - Univariate analysis (histograms)
   - Multivariate analysis (boxplots, scatter plots, correlation matrix)
   - Statistical tests (ANOVA, Kruskal-Wallis, chi-squared)

## Skills
- Performing univariate and multivariate statistical analysis
- Cleaning and preprocessing structured data
- Communicating results through clear and relevant visualizations

## Data Source
[Open Food Facts](https://world.openfoodfacts.org/)

