# Integrative Analysis of Multi-omics Data Characterize Epigenetics and Chromatin Dynamics in Mouse Models of Bleomyci n-Induced Lung Fibrosis
## Introduction
This project encompasses a series of Jupyter Notebook files and a Shell script for data downloading, which are essential for processing and analyzing biological data.

## File List and Descriptions
1. DownloadData.sh
This is a Shell script designed to seamlessly download all the prerequisite preprocessed data for the project. Make sure to run this script first to ensure you have the complete dataset before proceeding with the subsequent steps.

2. Step1_HiC_workflow.ipynb
This Notebook is dedicated to the initial processing and visualization workflow of Hi-C data. It covers the process from data ingestion to basic analysis, ensuring a comprehensive understanding of the dataset.

3. Step2_ATAC_workflow1.ipynb
This Notebook contains the first part of the ATAC-seq (Assay for Transposase Accessible Chromatin with high-throughput sequencing) workflow. It includes robust scripts for quality control and preliminary analysis of ATAC-seq data.

4. Step3_ATAC_workflow2.ipynb
Building on the first part, this Notebook continues the ATAC-seq analysis with more in-depth exploration and data mining techniques.

5. Step4_HiC_ATAC_workflow.ipynb
This Notebook integrates the analysis of Hi-C and ATAC-seq data, aiming to uncover relationships or combined effects between the two datasets.

6. Step5_RNA_workflow1.ipynb
The first part of the RNA-seq (RNA sequencing) workflow, which includes data processing and quality control steps, ensuring the integrity of the analysis.

7. Step6_RNA_workflow2.ipynb
The second part of the RNA-seq workflow, which involves more sophisticated analysis methods.

8. Step7_hic_fpkm.ipynb
This Notebook  integrates the analysis of Hi-C and RNA-seq data.

9. Step8_atac_fpkm.ipynb
Similarly to Step7, this Notebook  integrates the analysis of RNA-seq and ATAC-seq data, offering insights into the expression levels of accessible chromatin regions.

10. Step9_hic_atac_fpkm.ipynb
The final workflow Notebook, which integrates Hi-C, ATAC-seq and RNA-seq data to compute the ultimate FPKM values or other related metrics, summarizing the comprehensive analysis.

## Usage Guide
1. Ensure that you have a Python environment with the necessary libraries (e.g., pandas, numpy) installed.
2. Run DownloadData.sh to fetch the required data.
3. Open and execute each Jupyter Notebook file in the order listed above to complete the entire data analysis process.
4. Before running the scripts and notebooks, please review and update the configuration settings as needed to match your system’s environment and data structure.

## Notes
1. Make sure you have sufficient storage space to handle large biological datasets.
2. For complex operations, you may need to adjust memory allocation or optimize the code for enhanced efficiency.