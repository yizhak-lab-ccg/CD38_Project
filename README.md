# scRNAseq Analysis of ICI-Treated Patients

This page contains analysis scripts for scRNAseq datasets of melanoma and NSCLC patients treated with immune checkpoint inhibitors (ICI).

## Notebooks Overview

### 1. **Sade-Feldman et al. (Melanoma)**
This notebook performs scRNAseq analysis on a melanoma dataset. Key steps include:
- Loading and preprocessing the data.
- Log2 transformation of TPM counts.
- Exploratory analyses and visualization.

### 2. **Caushi et al. (NSCLC)**
This notebook performs scRNAseq analysis on a NSCLC dataset. Key steps include:
- Quality control of scRNAseq data.
- Analysis and visualization.

## Prerequisites

To reproduce the analyses, ensure you have the following dependencies installed:
- Python (>=3.8)
- Libraries: `numpy`, `pandas`, `seaborn`, `matplotlib`, `statsmodels`, `scipy`, `scikit-learn`, `scanpy`, `anndata`, `scrublet`

Install dependencies using:
```bash
pip install numpy pandas seaborn matplotlib statsmodels scipy scikit-learn scanpy anndata scrublet
```

## Data Sources

- The **Sade-Feldman et al. Melanoma** dataset, including patient metadata, clustering and tSNE coordinates, can be downloaded from the [Single-Cell Portal](https://singlecell.broadinstitute.org/single_cell/study/SCP398/defining-t-cell-states-associated-with-response-to-checkpoint-immunotherapy-in-melanoma).
- The **Caushi et al. NSCLC** dataset is available via [GSE176021](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE176021).

Ensure the datasets are saved in the appropriate directories according to your convenience.

## Repository Structure

```
CD38_Project/
|-- Sade_Feldman_et_al_Melanoma_analysis.ipynb
|-- Caushi_et_al_NSCLC_analysis.ipynb
```

## Citation

If you use this repository, please consider citing our paper with the relevant original studies:
- Revach et al.
- Sade-Feldman et al.
- Caushi et al.

---
For questions or issues, please contact ofirshorer@campus.technion.ac.il.
