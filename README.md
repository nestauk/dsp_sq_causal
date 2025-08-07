# Causal Inference Methods Testing

This repository implements and evaluates causal inference methods using the Infant Health and Development Program (IHDP) dataset as a benchmark.

## Data Setup

Download the IHDP dataset from [Kaggle](https://www.kaggle.com/datasets/konradb/ihdp-data/data) and place the `ihdp_data.csv` file in the `data/inputs/` directory.

```
data/
└── inputs/
    └── ihdp_data.csv
```

## Project Structure

- `notebooks/` - Jupyter notebooks for EDA and analysis
- `src/` - Python modules for causal inference methods
- `data/inputs/` - Raw data files

## Requirements

Python 3.12+ with dependencies managed via `uv`. Run `uv sync` to install all required packages.
