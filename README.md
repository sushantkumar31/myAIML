# myAIML

A hands-on machine learning fundamentals project using Jupyter notebooks.

## Project Structure

- `phase1.ipynb` — core ML mathematics and theory
  - Topic 1: Linear Algebra for ML
  - Topic 2: Calculus for ML
  - Topic 3: Probability & Statistics for ML
  - Topic 4: Information Theory for ML
- `phase2.ipynb` — practical data science workflows with Python
  - Topic 5: NumPy
  - Topic 6: Pandas
  - Topic 7: Data Visualization
  - Topic 8: Feature Engineering

## Requirements

- Python 3.13 or newer
- Dependencies are listed in `pyproject.toml`
  - `ipykernel`
  - `matplotlib`
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `seaborn`

## Getting Started

1. Create and activate a Python virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

> If `requirements.txt` does not exist, install from `pyproject.toml`:

```powershell
pip install -e .
```

3. Launch Jupyter Notebook:

```powershell
jupyter notebook
```

4. Open `phase1.ipynb` and `phase2.ipynb` and run the cells interactively.

## Notes

- `phase2.ipynb` produces several visualization outputs, including:
  - `01_histogram.png`
  - `02_scatter.png`
  - `03_boxplot.png`
  - `04_barplot.png`
  - `05_heatmap.png`
  - `06_pairplot.png`
  - `skew_correction.png`
  - `student_report.png`

- The notebooks are designed for learning foundational ML concepts and applying them directly with NumPy, Pandas, matplotlib, and seaborn.
