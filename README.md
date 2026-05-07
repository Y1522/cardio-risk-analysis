# Cardiovascular Risk Mining (Notebook)

This project is a Jupyter notebook pipeline for exploring a cardiovascular dataset, performing preprocessing/feature scaling, running clustering (e.g., agglomerative clustering, k-medoids, fuzzy logic), and training a baseline classifier (logistic regression).

## What’s in this folder

- `Project.ipynb`: the notebook.
- `health_data.csv`: the dataset file expected by the notebook (must be in the same folder).
- `requirements.txt`: Python dependencies to run the notebook.

## Setup (Windows / PowerShell)

From this directory:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Run

```powershell
jupyter lab
```

Then open `Project.ipynb` and run the cells top-to-bottom.

## Notes

- If you see an error like “`health_data.csv` not found”, place the CSV in this same directory as `Project.ipynb`.
- If you don’t have Python installed, install Python 3.10+ and ensure the `py` launcher works in PowerShell.

