# Results

This folder contains the output files generated from the Differential Gene Expression (DEG) analysis of Alzheimer’s disease using GEO2R.

## Files Included

### 1. GSE5281.top.table.tsv
Full differential expression results table downloaded from GEO2R.

This file includes:
- Gene identifiers
- log2 Fold Change (log2FC)
- P-values
- Adjusted P-values (Benjamini–Hochberg correction)

This table was used to identify significant differentially expressed genes based on:
- Adjusted p-value < 0.05
- |log2 Fold Change| ≥ 1

---

### 2. volcano_plot.png
Volcano plot visualization of the differential gene expression results.

- Red points represent significantly upregulated genes.
- Blue points represent significantly downregulated genes.
- Black points represent non-significant genes.

The plot illustrates the transcriptional differences between Alzheimer’s disease and control samples in the Entorhinal Cortex (GSE5281 dataset).

---

These files represent the processed analysis outputs used in the final project report.
