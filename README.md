# R-script---Hashimoto-s-thyroiditis-DExMA-
# Meta-analysis of HT and PTC Gene Expression Datasets

This repository contains R scripts and relevant files for reproducing the meta-analysis presented in our manuscript:  
**"Identification of Key Genes and Regulatory Pathways in Hashimoto’s Thyroiditis and Papillary Thyroid Carcinoma"**

##  Contents
- `1_preprocessing.R`: Data preprocessing and normalization
- `2_meta_analysis.R`: Meta-analysis using DExMA package
- `3_figures.R`: Code to generate figures in the manuscript
- `data/`: Contains processed data used in the analysis
- `results/`: Outputs and result tables

##  Datasets
Two GEO datasets were used in this study:
- **GSE138198** (Affymetrix HuGene 1.0 ST)
- **GSE29315** (Affymetrix HG_U95Av2)

##  Requirements
- R (>= 4.2.0)
- Bioconductor packages: `DExMA`, `Biobase`, `limma`, etc.

