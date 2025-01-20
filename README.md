# Multi-Omics Breast Cancer Analysis
## **In progress** 

This project performs a **multi-omics** analysis of breast cancer data, integrating **transcriptomics**, **genomics**, and **epigenomics** data. The ultimate goal is to apply machine learning methods to uncover patterns in the data that are predictive of clinical diagnoses and outcomes. </br> </br>

## Data Overview

The project uses data from the **TCGA-BRCA** dataset, focusing on the following data:

### 1. **Transcriptomics**
- **FPKM (Fragments Per Kilobase of transcript per Million mapped reads)** data from **RNA-Seq**: Reflects the level of gene expression across various breast cancer samples

### 2. **Genomics**
- **Copy Number Variations (CNVs)** at the gene level: Regions of the genome where the number of copies of certain genes is altered in cancerous cells.

### 3. **Epigenomics**
- **DNA Methylation** data from the **Illumina Human Methylation 450** array: Contains information on methylation patterns across the genome.

### 4. **Clinical and Survival Data**
- Clinical information from the **TCGA-BRCA** cohort: Includes patient demographics, tumor characteristics, and survival data.
- This data will be used for clinical outcome prediction and survival analysis. </br> </br>

## Data Sources
The data used in this project is obtained from the following sources:

1. **Transcriptomics (FPKM data)**
   - [TCGA-BRCA STAR FPKM](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.star_fpkm.tsv&host=https%3A%2F%2Fgdc.xenahubs.net)
   
2. **Genomics (Copy Number Variations)**
   - [Gene Level Copy Number (ABSOLUTE)](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.gene-level_absolute.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)
   
3. **Epigenomics (DNA Methylation)**
   - [Illumina Human Methylation 450](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.methylation450.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)

4. **Clinical and Survival Data**
   - [TCGA-BRCA Clinical Data](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)
   - [TCGA-BRCA Survival Data](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.survival_data.tsv&host=https%3A%2F%2Fgdc.xenahubs.net](https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.survival.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443) </br> </br>

## Objectives and Future Directions
The goal of this project is to:

1. Perform exploratory data analysis on transcriptomics, genomics, and epigenomics data to uncover potential patterns associated with breast cancer.
2. Applying deep learning models (e.g., fully connected networks, 1D CNNs, and transformers) to classify breast cancer samples based on multi-omics features.
3. Integrate clinical and survival data to predict clinical outcomes and improve our understanding of the factors influencing breast cancer progression. </br> </br>
