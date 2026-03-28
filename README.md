# Binary Prediction with a Rainfall Dataset

![Python](https://img.shields.io/badge/python-3.10%2B-3776AB?style=flat&logo=python&logoColor=white)
![Notebook](https://img.shields.io/badge/notebook-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-learning%20repository-57606a)

## What is this

A notebook-based binary classification workflow on rainfall-related tabular data.

## Why it exists

This repository preserves a compact applied-ML case study and supports model experimentation practice.

## Architecture / Stack

- Python, pandas, numpy
- scikit-learn
- Jupyter Notebook

## Installation

```bash
git clone https://github.com/fbenkhelifa/binary-prediction-with-a-rainfall-dataset.git
cd binary-prediction-with-a-rainfall-dataset
python -m venv .venv
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## Usage

Run `binary-prediction-with-a-rainfall-dataset.ipynb` top-to-bottom in Jupyter/VS Code.

## Project structure

```text
binary-prediction-with-a-rainfall-dataset/
├── binary-prediction-with-a-rainfall-dataset.ipynb
├── README.md
├── .gitignore
└── LICENSE
```

## Limitations

- Notebook-only implementation
- No automated tests or CI pipeline

## Roadmap

1. Move notebook logic into reusable Python modules.
2. Add reproducible requirements lock file.
3. Add evaluation summary report.

## License

MIT License (see `LICENSE`).