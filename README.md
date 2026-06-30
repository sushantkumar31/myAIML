# myAIML

This repository contains a two-part introduction to machine learning and data science using Jupyter notebooks. It combines foundational theory with practical Python workflows for numerics, data manipulation, visualization, and feature engineering.

## Project Structure

- `phase1.ipynb` — foundational machine learning concepts
  - Linear algebra for ML
  - Calculus for ML
  - Probability and statistics for ML
  - Information theory for ML

- `phase2.ipynb` — hands-on data science practice with Python
  - NumPy arrays, broadcasting, and vectorized ML operations
  - Pandas data cleaning, filtering, grouping, and feature engineering
  - Data visualization with Matplotlib and Seaborn
  - Exploratory data analysis workflow and preprocessing examples

## Requirements

- Python 3.13 or newer
- Dependencies are defined in `pyproject.toml`
  - `ipykernel`
  - `matplotlib`
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `seaborn`

## Getting Started

1. Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install the project and dependencies:

```powershell
pip install -e .
```

3. Start Jupyter:

```powershell
jupyter notebook
```

4. Open `phase1.ipynb` and `phase2.ipynb` and run the cells interactively.

## Notes

- `phase2.ipynb` may generate visualization outputs in the repository folder, such as:
  - `01_histogram.png`
  - `02_scatter.png`
  - `03_boxplot.png`
  - `04_barplot.png`
  - `05_heatmap.png`
  - `06_pairplot.png`
  - `skew_correction.png`
  - `student_report.png`

- The notebooks are intended for learning core ML concepts and applying them directly with NumPy, Pandas, Matplotlib, and Seaborn.

