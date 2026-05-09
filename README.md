# Transcriptomic Analysis of Tumor-Normal Gene Expression Profiles Using RNA-seq Data
## Overview

This project presents a transcriptomic analysis workflow for studying tumor-normal gene expression differences using RNA-seq datasets obtained from the Gene Expression Omnibus (GEO) repository of the National Center for Biotechnology Information (NCBI).The project focuses on preprocessing transcriptomic count data, performing normalization and differential gene expression analysis, and identifying significantly dysregulated genes associated with disease progression. The workflow integrates computational biology, transcriptomics, and bioinformatics methodologies for exploratory cancer-related gene expression analysis.
The study demonstrates a reproducible RNA-seq analysis pipeline using DESeq2-based workflows implemented in Python for transcriptomic profiling and biomarker-oriented investigation.
---
## Research Objectives
- Perform transcriptomic preprocessing and normalization of RNA-seq datasets
- Conduct tumor vs normal comparative gene expression analysis
- Identify significantly differentially expressed genes (DEGs)
- Explore transcriptomic separation patterns between biological conditions
- Generate biologically interpretable transcriptomic signatures
- Establish a computational workflow for downstream biomarker discovery studies
---
## Dataset Used
The project utilizes RNA-seq transcriptomic datasets from the GEO repository hosted by NCBI.
### Dataset Characteristics
- Gene expression count matrices
- Tumor and normal sample groups
- Transcriptomic expression profiles for comparative analysis
- Preprocessed RNA-seq count data for downstream differential expression workflows
---
## Methodology
### 1. Data Preprocessing
The transcriptomic datasets were preprocessed to prepare them for downstream statistical analysis.
#### Preprocessing Steps
- Removal of non-essential annotation columns
- Handling missing expression values
- Correction of zero-value entries
- Integer conversion of count matrices
- Metadata generation for sample classification
- Preparation of count matrices for DESeq2 analysis
---
### 2. Differential Expression Analysis
Differential gene expression analysis was performed using DESeq2-based statistical workflows through PyDESeq2.
#### Analysis Workflow
- Tumor vs normal transcriptomic comparison
- Dispersion estimation
- Statistical significance testing
- Fold-change computation
- Adjusted p-value filtering for significant genes
---
### 3. Exploratory Transcriptomic Analysis
Exploratory analysis was conducted to evaluate transcriptomic variation across biological conditions.
#### Analytical Approaches
- Principal Component Analysis (PCA)
- Transcriptomic distribution analysis
- Expression pattern visualization
- Comparative transcriptomic profiling
---
### 4. Transcriptomic Interpretation
The analysis generated biologically meaningful transcriptomic signatures that can support downstream studies in:
- biomarker discovery
- systems biology
- functional genomics
- computational oncology research
---
## Tools and Technologies
### Programming Language
- Python
### Libraries and Frameworks
- Pandas
- NumPy
- Scikit-learn
- PyDESeq2
- Matplotlib
- Seaborn
- Scanpy
- Biopython
---
## Key Features
- RNA-seq transcriptomic preprocessing pipeline
- Tumor-normal comparative transcriptomic analysis
- Differential gene expression analysis
- DESeq2-based statistical workflow
- Exploratory transcriptomic visualization
- Biomarker-oriented transcriptomic interpretation
---
## Applications
- Computational biology research
- Cancer transcriptomics
- Differential gene expression studies
- Bioinformatics workflow development
- Biomarker discovery research
- RNA-seq analytical pipeline development
---
## Workflow
```text
GEO RNA-seq Dataset
        ↓
Data Cleaning & Preprocessing
        ↓
Metadata Construction
        ↓
Normalization Preparation
        ↓
Differential Expression Analysis
        ↓
Tumor vs Normal Comparison
        ↓
Exploratory Transcriptomic Analysis
        ↓
Biological Interpretation
```
### Working Website: 
https://somshirsha.github.io/Transcriptomic-Analysis-of-Tumor-Normal-Gene-Expression-Profiles-Using-RNA-seq-Data/
