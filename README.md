# Relection Homework

Coursework for [Experimental Design and Causality] ([Summer, 2026]). This repository contains a series of Jupyter notebooks for the weekly reflections.

## Contents

| Notebook | Topics |
| --- | --- |
| `homework_1.ipynb` | OLS regression and omitted-variable bias (simple vs. multivariate slopes); nearest-neighbor matching to estimate a treatment effect |
| `homework_2.ipynb` | Within-group demeaning for a common slope; bootstrap inference (variance, skewness) for naive difference-in-means vs. OLS treatment effects |
| `homework_3.ipynb` | Regression discontinuity design (RDD) around a cutoff; difference-in-differences (DiD) |
| `homework_4.ipynb` | Instrumental variables (Wald estimator, first stage / reduced form, covariate-stratified IV); regression discontinuity with a binary outcome |

## Data

The notebooks read their datasets from CSV files in the same directory, for example `homework_1.1.csv`, `homework_2.1.csv`, `homework_3.2.a.csv`, and so on. These files must be present for the notebooks to run end to end. 

## Requirements

The notebooks use:

- Python 3.12
- `pandas`
- `numpy`
- `scipy`
- `statsmodels`
- `scikit-learn`
- `matplotlib`

Install them with:

```bash
pip install pandas numpy scipy statsmodels scikit-learn matplotlib
```

## Running

Open any notebook in Jupyter and run the cells in order:

```bash
jupyter notebook
```

## Author

[Kristan German]
