# Stage_gene_exp
Tools for gene expression analysis

This repository contains Excel files for data analysis of the TCGA Breast Carcinoma dataset (42851 transcripts for 1250 patients, file is available upon request).
Genes related to histone methylation (writers, readers, and erasers) are examined for expression variance across molecular subtypes, and survival analysis is performed.

It also contains several Jupyter notebooks:

02_project+file+ANOVA.ipynb - sample grouping and ANOVA analysis

04_survival_analysis.ipynb - survival analysis of a selection of genes

Correlation.ipynb - expression correlation analysis and heatmap rendering for selected genes

NCBI prompts.ipynb - a tool that prompts NCBI based on a given list of gene names (as strings) and retrieves all their synonymic names from their NCBI pages.
This can be used for analysis enrichment.
