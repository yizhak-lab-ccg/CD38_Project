# scRNAseq Analysis of ICI-Treated Patients

This repository contains analysis scripts for scRNAseq datasets of patients treated with immune checkpoint inhibitors (ICI). These analyses focus on understanding cellular and molecular responses in melanoma and non-small cell lung cancer (NSCLC).

## Notebooks Overview

### 1. **Sade-Feldman et al. (Melanoma)**
This notebook performs scRNAseq analysis on a melanoma dataset. Key steps include:
- Loading and preprocessing the data.
- Log2 transformation of TPM counts.
- Exploratory analyses and visualization.

### 2. **Caushi et al. (NSCLC)**
This notebook processes an NSCLC dataset to examine patient-specific and treatment-specific responses. Key steps include:
- Quality control of scRNAseq data.
- Statistical analyses and visualization of key findings.

## Prerequisites

To reproduce the analyses, ensure you have the following dependencies installed:
- Python (>=3.8)
- Libraries: `numpy`, `pandas`, `seaborn`, `matplotlib`, `statsmodels`, `scipy`, `scikit-learn`, `scanpy`, `anndata`, `scrublet`

Install dependencies using:
```bash
pip install numpy pandas seaborn matplotlib statsmodels scipy scikit-learn scanpy anndata scrublet
```

## Running the Notebooks

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/scRNAseq_ici_analysis.git
   cd scRNAseq_ici_analysis
   ```

2. Open the notebooks in Jupyter or any compatible environment:
   ```bash
   jupyter notebook
   ```

3. Navigate to the respective notebook and follow the instructions within to reproduce the results.

## Data Sources

- The **Sade-Feldman** dataset can be downloaded from the [Single-Cell Portal](https://singlecell.broadinstitute.org/single_cell).
- The **Caushi** dataset is available via [link or repository] (update with source).

Ensure the datasets are saved in the appropriate directories as specified in the notebooks.

## Repository Structure

```
scRNAseq_ici_analysis/
|
|-- Sade_Feldman_et_al_Melanoma_analysis.ipynb
|-- Caushi_et_al_NSCLC_analysis.ipynb
|-- data/  # Folder for storing raw datasets
|-- results/  # Folder for saving analysis outputs
```

## Citation

If you use this repository, please cite the original studies:
- Sade-Feldman M et al.
- Caushi JX et al.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---
For questions or issues, please contact [ofirshorer@campus.technion.ac.il].
