# Selective Sweep Analysis

This repository contains a Jupyter Notebook for performing selective sweep analysis on genomic data. The analysis focuses on identifying regions of the genome that may have undergone recent positive selection using Zhp statistics.

## Notebook

**File:** selective_sweep_analysis-800kb-Zhp1.ipynb

**Purpose:** Analyze genomic data to detect signatures of selective sweeps in windows using the Zhp statistic.

**Input:** Genomic variant data (VCF or preprocessed data in compatible formats).

**Output:** Plots and tables highlighting genomic regions potentially under positive selection.

## Dependencies

This notebook requires the following Python packages:

numpy

pandas

matplotlib

seaborn

scipy

jupyter

You can install them via pip:

```
pip install numpy pandas matplotlib seaborn scipy jupyter
```

## Usage

Clone the repository
```
git clone https://github.com/yaqoobcs/selective-sweep-implementation.git
cd selective-sweep-analysis
```
Open the Notebook
```
jupyter notebook selective_sweep_analysis-800kb-Zhp1.ipynb
```

Follow the notebook cells to
- Load your data
- Compute Zhp statistics
- Visualise selective sweep regions


# Output

The notebook generates:
- Genome-wide Zhp plots
- Tables of candidate regions with potential selective sweeps
- Optional summary statistics and visualisations

# Notes

- Ensure that your input data is properly formatted.
- Adjust window sizes and thresholds as necessary for your dataset.
- The notebook is designed for exploratory analysis; further statistical validation is recommended.
