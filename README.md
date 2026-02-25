<h1>Glioblastoma Proteostasis Target Prioritization</h1>
Proteogenomic Identification of Proteostasis Dependencies in Glioblastoma

---

This project uses quantitative tumor proteomics as the primary discovery layer to identify dysregulated proteostasis pathways and prioritize protein-level therapeutic vulnerabilities. Transcriptomic and dependency data are used only for orthogonal validation.
This repository documents an **ongoing independent research project**. 

Which proteostasis-associated proteins represent essential and therapeutically actionable dependencies in glioblastoma?
---

## Data Sources
- Clinical Proteomic Tumor Analysis Consortium — quantitative proteomics
- The Cancer Genome Atlas — transcriptomics and clinical data
- DepMap — CRISPR gene dependency scores

---
## Analytical Strategy

### Proteome-Level Dysregulation
- Differential protein abundance analysis
- Effect size prioritization
- Variability assessment
- Missingness filtering
- Proteome-wide statistical correction

### Proteostasis Network Enrichment
Focused analysis of:
- Heat shock proteins
- Co-chaperones
- UPR mediators
- Proteasome components
- ER stress regulators
Pathway enrichment using protein-level data

### Protein–Transcript Concordance
Evaluate:
- Protein–mRNA correlation
- Identification of post-transcriptionally regulated proteins
- Proteins dysregulated independently of mRNA are prioritized, as they indicate proteome-level control.

### Clinical Proteomics
- Survival association using protein abundance
- Covariate adjustment

### Functional Validation Layer
- Cross-reference with CRISPR dependency data
- Evaluate essentiality in GBM models

---
## Output
A ranked set of proteostasis-associated proteins:
- Dysregulated at the protein level
- Clinically associated
- Functionally essential
- Mechanistically linked to stress adaptation

---
## Proposed Experimental Validation
- Targeted proteomics (PRM/SRM)
- Protein stability assessment
- Knockdown and stress-response assays
- Drug perturbation experiments
---
