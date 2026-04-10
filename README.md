# Stage_gene_exp
Tools for gene expression analysis

Genes related to histone methylation (writers, readers, and erasers) are examined for expression variance across molecular subtypes of breast cancer.
Survival analysis is performed on the differently expressed genes.

expression_data_tcga_brca_TCGA-BRCA_log_fpkm_1226_samples_466_genes.csv - trimmed dataset is used, filtered to retain genes of interest only (466 genes). Original file with 42851 transcripts is availavle upon request.

KDMs list.xlsx, Candidate_KMTs.xlsx, putative KMe binding domain containing proteins.xlsx - lists of genes of interest

EpiMed_experimental_grouping_2023.03.16_TCGA-BRCA.xlsx and clinical_TCGA-BRCA.csv - clinical data for samples, including the subtype and stage of disease

02_project+file+ANOVA.ipynb - sample grouping and ANOVA analysis

04_survival_analysis.ipynb - survival analysis of a selection of genes

NCBI prompts.ipynb - a tool that prompts NCBI based on a given list of gene names (as strings) and retrieves all their synonymic names from their NCBI pages.
This can be used for analysis enrichment.
