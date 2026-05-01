# Transcriptomic Analysis and ceRNA Network Construction in Glioblastoma

## Overview

This project focuses on transcriptomic analysis of glioblastoma using RNA-seq and microarray datasets obtained from the Gene Expression Omnibus (GEO) database of the National Center for Biotechnology Information (NCBI). The study investigates the regulatory roles of coding and non-coding RNAs in glioblastoma progression through differential gene expression analysis, transcriptomic profiling, and gene regulatory network construction.

The workflow integrates bioinformatics preprocessing, normalization, exploratory transcriptomic analysis, pathway enrichment analysis, and biomarker identification using computational biology and machine learning-oriented approaches.

---

## Research Objectives

* Analyze transcriptomic datasets related to glioblastoma progression.
* Identify differentially expressed coding and non-coding RNAs.
* Perform transcriptomic normalization and tumor-normal comparative analysis.
* Construct gene regulatory and ceRNA interaction networks.
* Identify potential biomarker genes and therapeutic targets.

---

## Datasets Used

* RNA-seq and transcriptomic datasets from the NCBI GEO repository.
* Tumor and normal sample expression profiles.
* Gene expression matrices processed for downstream differential expression analysis.

---

## Methodology

### Data Preprocessing

* Removed non-essential transcript annotation columns.
* Processed transcriptomic count matrices.
* Performed integer conversion and normalization preparation for differential expression analysis.
* Handled missing and zero-value expression entries.

### Differential Expression Analysis

* Implemented differential expression analysis using DESeq2-based workflows.
* Performed tumor vs normal transcriptomic comparison.
* Identified significantly dysregulated genes using fold-change and adjusted p-value thresholds.

### Transcriptomic Analysis

* Conducted PCA-based exploratory transcriptomic analysis.
* Visualized transcriptomic separation between tumor and normal samples.
* Generated expression-based analytical outputs for downstream interpretation.

### Functional and Pathway Enrichment Analysis

* Performed gene set enrichment analysis (GSEA).
* Evaluated biological pathway enrichment using ranked transcriptomic signatures.

### Network Construction

* Constructed gene regulatory and ceRNA interaction networks.
* Identified biomarker-associated interaction patterns for therapeutic target exploration.

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Biopython
* PyDESeq2
* Scanpy
* GSEApy
* Seaborn

---

## Key Features

* RNA-seq transcriptomic preprocessing pipeline
* Differential gene expression analysis
* Tumor-normal transcriptomic profiling
* Pathway enrichment analysis
* ceRNA and gene regulatory network construction
* Biomarker identification workflow

---

## Applications

* Computational oncology research
* Biomarker discovery
* Transcriptomic analysis in cancer biology
* Bioinformatics-driven therapeutic target identification
* Systems biology and network biology analysis

---

## Project Type

Research Project | Computational Biology | Bioinformatics | Transcriptomics | Cancer Genomics

