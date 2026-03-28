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
# optional: install kaggle CLI and configure ~/.kaggle/kaggle.json
powershell -ExecutionPolicy Bypass -File scripts/download_data.ps1
```

## Usage

Run `notebooks/rainfall-binary-prediction.ipynb` top-to-bottom in Jupyter/VS Code.

Dataset files are expected under `data/raw/kaggle_s5e3/`.

## Project structure

```text
binary-prediction-with-a-rainfall-dataset/
├── data/
│   ├── README.md
│   ├── raw/
│   │   └── kaggle_s5e3/
│   └── processed/
├── notebooks/
│   └── rainfall-binary-prediction.ipynb
├── reports/
│   └── .gitkeep
├── src/
│   └── .gitkeep
├── scripts/
│   └── download_data.ps1
├── README.md
├── .gitignore
└── LICENSE
```

## Limitations

- Notebook-only implementation
- Competition data is not redistributed in this repository
- No automated tests or CI pipeline

## Roadmap

1. Move notebook logic into reusable Python modules.
2. Add reproducible requirements lock file.
3. Add evaluation summary report.

## License

MIT License (see `LICENSE`).