# Multi-Omics Breast Cancer Analysis

This project performs a **multi-omics** analysis of breast cancer data, integrating **transcriptomics**, **genomics**, and **epigenomics** data to explore gene expression, genetic variations, and epigenetic modifications. The ultimate goal is to apply machine learning methods to uncover patterns in the data that are predictive of clinical outcomes, advancing our understanding of the biological mechanisms underlying breast cancer.

## Data Overview

The project uses data from the **TCGA-BRCA** dataset, focusing on the following types of omics data:

### 1. **Transcriptomics**
- **FPKM (Fragments Per Kilobase of transcript per Million mapped reads)** data from **RNA-Seq**.
- This data reflects the level of gene expression across various breast cancer samples and will be used for feature extraction and downstream machine learning modeling.

### 2. **Genomics**
- **Copy Number Variations (CNVs)** at the **gene level**. CNVs refer to regions of the genome where the number of copies of certain genes is altered in cancerous cells.
- CNV data will provide insights into genomic instability and its correlation with cancer progression.

### 3. **Epigenomics**
- **DNA Methylation** data from the **Illumina Human Methylation 450** array.
- This dataset contains information on methylation patterns across the genome, which can influence gene expression and may play a role in cancer development.

### 4. **Clinical and Survival Data**
- Clinical information from the **TCGA-BRCA** cohort, which includes patient demographics, tumor characteristics, and survival data.
- This data will be used for clinical outcome prediction and survival analysis.

## Data Sources

The data used in this project is obtained from the following sources:

1. **Transcriptomics (FPKM data)**
   - [TCGA-BRCA STAR FPKM](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.star_fpkm.tsv&host=https%3A%2F%2Fgdc.xenahubs.net)
   
2. **Genomics (Copy Number Variations)**
   - [Gene Level Copy Number (ABSOLUTE)](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.ABSOLUTE.gene_level_CN.tsv&host=https%3A%2F%2Fgdc.xenahubs.net)
   
3. **Epigenomics (DNA Methylation)**
   - [Illumina Human Methylation 450](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.methylation_450.tsv&host=https%3A%2F%2Fgdc.xenahubs.net)

4. **Clinical and Survival Data**
   - [TCGA-BRCA Clinical Data](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net)
   - [TCGA-BRCA Survival Data](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.survival_data.tsv&host=https%3A%2F%2Fgdc.xenahubs.net)

## Objective

The goal of this project is to:

1. Perform exploratory data analysis on transcriptomics, genomics, and epigenomics data to uncover potential patterns associated with breast cancer.
2. Use machine learning models to classify breast cancer samples based on gene expression (transcriptomics), copy number alterations (genomics), and methylation patterns (epigenomics).
3. Integrate clinical and survival data into the analysis to predict clinical outcomes and improve our understanding of the factors influencing breast cancer progression.

## Future Directions

This is an ongoing project, and some of the future goals include:

- Expanding the analysis with additional omics data types such as proteomics or metabolomics if available.
- Applying deep learning models (e.g., fully connected networks, 1D CNNs, and transformers) to handle complex multi-omics data.
- Exploring potential relationships between different types of omics data and their role in breast cancer prognosis.
