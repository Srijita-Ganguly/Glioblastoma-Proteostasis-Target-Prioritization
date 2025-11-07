# Gene Expression Heatmap and Functional Enrichment Analysis

## Overview

This project involves visualization and interpretation of gene expression datasets to generate heatmaps and perform downstream functional enrichment analysis. The goal is to understand gene expression patterns and their biological significance in the context of differential expression.

---

## Project Tasks

### 1. Data Acquisition
Downloading and using one of the following datasets, which contain over 500 differentially expressed genes under various conditions:

- [Cancer2024 - Glioblastoma](https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/Cancer2024/glioblastoma.csv)
- [Cancer2024 - Pregnancy Lactation Cells](https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/Cancer2024/pregnancyLactationCells.csv)

### 2. Exploring External Resources
Visit the [Cancer Page of the Human Proteome Atlas](https://www.proteinatlas.org/humanproteome/cancer) and selecting a proteome with an unfavorable prognosis related to your chosen cancer type.

### 4. Heatmap Generation

- Generating a heatmap for the entire dataset.
- Using a diverging and sequential color palette to display the data effectively.
- Carefully selecting the color scheme to enhance interpretability.
- Writing a detailed interpretation of your heatmap in the project report.
- Using the `heatmap.2()` function from the `gplots` R package.

### 5. Clustering Variants

Generating variants of your heatmap by clustering:

- Genes (rows) alone  
- Samples (columns) alone  
- Both genes and samples together

### 6. Subsetting Significantly Regulated Genes

- Subset genes significantly **upregulated** (based on fold change and p-value cut-offs).  
- Subset genes significantly **downregulated** similarly.

### 7. Functional Enrichment Analysis

Performing enrichment analysis using any of the following tools:

- [ShinyGO](http://bioinformatics.sdstate.edu/go/)  
- [GOrilla](http://cbl-gorilla.cs.technion.ac.il/)  
- [PANTHER](http://pantherdb.org/)

### 8. Pathway Visualization

Using the top 10 enriched pathways, creating a clear visualization such as:

- Lollipop plot  
- Bubble plot  

These plots represent the number of genes associated with each pathway.

---
