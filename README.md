# Stage_gene_exp
Tools for gene expression analysis

This repository contains Excel files for data analysis of the TCGA Breast Carcinoma dataset (42851 transcripts for 1250 patients, file is available upon request).
Genes related to histone methylation (writers, readers, and erasers) are explored for expression variance between the groups (different stages, N-stages, and molecular subtypes), and survival analysis is performed.

It contains also several Jupyter notebooks:
02_project+file+ANOVA.ipynb - sample grouping and ANOVA analysis (needs to be updated)
04_survival_analysis.ipynb - survival analysis of genes in the selected groups
Correlation.ipynb - expression correlation analysis and heatmap rendering for selected genes
NCBI prompts.ipynb - a tool that prompts NCBI based on a given list of gene names (as strings) and retrieves all their synonymic names from their NCBI pages.
This can be used for analysis enrichment.
