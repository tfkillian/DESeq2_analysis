# DESeq2_analysis

This repository contains template R scripts to perform analysis of bulk omic count data

## Bulk RNA-Seq Analysis with DESeq2 and GSEA

This repository contains two R Markdown scripts that illustrate a typical bulk
RNA-Seq analysis workflow using DESeq2 and subsequent GSEA (gene set enrichment
analysis) of the differentially expressed genes.

- `DESeq2_BulkRNAseq.Rmd` Performs differential expression analysis of bulk RNA-seq counts using DESeq2.
- `GSEA_DE_Analysis.Rmd` Performs GSEA on the results (ranked gene list) obtained from the DESeq2 analysis.

Prerequisites

- R (>= 4.0) or newer
- RStudio (optional but recommended)
- R packages:
- DESeq2
- tidyverse (or at least dplyr, tidyr, ggplot2, etc.)
- fgsea
- hypeR
- PPInfer (for GSEA bar plot function)
- writexl
- DT
