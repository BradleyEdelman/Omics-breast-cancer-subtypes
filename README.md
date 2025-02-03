# Multi-Omics Pan-Cancer Analysis
## **In progress** 

This project aims to perform a **multi-omics** analysis of the TCGA Pan-Cancer (PANCAN) cohort, integrating **transcriptomics**, **genomics**, and **epigenomics** data. The ultimate goal is to apply machine learning methods to uncover patterns in the data that are predictive of clinical diagnoses and outcomes. </br> </br>

## Data Overview

The project uses data from the **TCGA-BRCA** dataset, focusing on the following data:

### 1. **Transcriptomics**
- **Gene Expression (RSEM TPM):** Gene expression levels using Transcripts Per Million (TPM) normalization
- [TCGA-PANCAN TOIL RSEM TPM](https://xenabrowser.net/datapages/?dataset=tcga_RSEM_gene_tpm&host=https%3A%2F%2Ftoil.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)
  
### 2. **Genomics**
- **Copy Number Variations (GISTIC2 thresholded):** Regions of the genome where the number of copies of certain genes is altered in cancerous cells.
- [TCGA-PANCAN CNV]([https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.gene-level_absolute.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443](https://xenabrowser.net/datapages/?dataset=TCGA.PANCAN.sampleMap%2FGistic2_CopyNumber_Gistic2_all_thresholded.by_genes&host=https%3A%2F%2Ftcga.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443))
- **Gene Mutations:** Lists non-silent mutations in genes across cancer samples.
- [TCGA-PANCAN Mutation Status]([https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.gene-level_absolute.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443](https://xenabrowser.net/datapages/?dataset=mc3.v0.2.8.PUBLIC.nonsilentGene.xena&host=https%3A%2F%2Fpancanatlas.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443))
  
### 3. **Epigenomics**
- **DNA Methylation:** DNA methylation patterns across genes.
- [TCGA-PANCAN Methylation 450]([https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.methylation450.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443](https://xenabrowser.net/datapages/?dataset=jhu-usc.edu_PANCAN_HumanMethylation450.betaValue_whitelisted.tsv.synapse_download_5096262.xena&host=https%3A%2F%2Fpancanatlas.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443))
  
### 4. **Clinical/Survival Data**
- Clinical information from the **TCGA-PANCAN** cohort: Includes patient demographics, cancer characteristics, and survival data.
- [TCGA-PANCAN Clinical Data]([https://xenabrowser.net/datapages/?dataset=TCGA-BRCA.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443](https://xenabrowser.net/datapages/?dataset=Survival_SupplementalTable_S1_20171025_xena_sp&host=https%3A%2F%2Fpancanatlas.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)) </br> </br>

## Objectives and Future Directions
The goal of this project is to:

1. Perform exploratory data analysis on transcriptomics, genomics, and epigenomics data to uncover potential patterns associated with breast cancer.
2. Applying deep learning models (e.g., fully connected networks, 1D CNNs, and transformers) to classify breast cancer samples based on multi-omics features.
3. Integrate clinical and survival data to predict clinical outcomes and improve our understanding of the factors influencing breast cancer progression. </br> </br>
