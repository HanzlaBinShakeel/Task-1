# Task 1: Exploring and Visualizing the Iris Dataset

## Objective
Learn to load, inspect, and visualize a dataset to understand trends and distributions.

## Dataset
**Iris Dataset** — 150 samples, 4 features (`sepal_length`, `sepal_width`, `petal_length`, `petal_width`), 3 species. Loaded via `seaborn.load_dataset('iris')`.

## What We Did
- Loaded data with **pandas**; printed shape, columns, `.head()`, `.info()`, `.describe()`
- **Scatter plots** (pairplot + focused scatter) for feature relationships
- **Histograms** for value distributions
- **Box plots** for outlier detection

## Key Results
- No missing values; balanced 50 samples per species
- Petal measurements best separate species; setosa is easily distinguishable
- Few outliers — ideal for EDA practice

## Files
| File | Description |
|------|-------------|
| `iris_exploration.ipynb` | Main Jupyter notebook |

## Run
```bash
jupyter notebook iris_exploration.ipynb
```
