Multi-Model Machine Learning Analysis of TCGA-LIHC RNA-Seq Data for Tumor Classification and Robust Gene Discovery

**Project Overview**
This project applies multiple machine learning models to TCGA Liver Hepatocellular Carcinoma (LIHC) RNA-seq data to classify tumor vs normal samples and identify robust tumor-associated genes. To reduce model-specific bias, feature importance results from Logistic Regression, Random Forest, and XGBoost are compared to identify consensus genes consistently ranked across models.

**Dataset**
Total samples: 424 
Tumor: 371 
Normal: 53 
Data type: STAR-aligned, log₂-normalized gene-level RNA-seq expression 
Cancer type: TCGA-LIHC (Liver Hepatocellular Carcinoma)

**Data Sources**
Gene expression data:[TCGA-LIHC STAR-aligned gene-level RNA-seq data](https://gdc-hub.s3.us-east-1.amazonaws.com/download/TCGA-LIHC.star_counts.tsv.gz)
Clinical Survival data: [TCGA-LIHC clinical survival data](https://xenabrowser.net/datapages/?dataset=TCGA-LIHC.survival.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)
