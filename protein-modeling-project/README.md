# 🧬 Protein Structure Visualization and Analysis

## 📘 Overview
This project explores **computational biology** by performing **homology modeling** and using **AlphaFold** and **SWISS-MODEL** to predict, model, and visualize protein structures using **PyMol**.  
Comparison of modeling techniques, analyze 3D protein structures, and evaluate which approach provides the most accurate results.

---

## 🎯 Project Objectives
- To Model and visualize the **protein structure** pf **p53** important in cancer research.  
- Comparing the **Homology Modeling** vs **AlphaFold** predictions.  
- Using visualization tools like PyMOL to explore and analyze 3D models.  
- Evaluating accuracy and reliability of different prediction methods.
---

## 🧩 Workflow

### 1. Protein selection
🧬 **p53** and Its Role in Cancer: p53 is one of the important tumor suppressor. It controls cell division, DNA repair and apoptosis. Mutation in TP53 gene lead to loss of tumor suppression. 
In clinical oncology, p53 status is an important biomarker for cancer prognosis and treatment response.

---

### 2. Downloading the Protein Structure
- PDB website(https://www.rcsb.org/)  

---

### 3. Performing Homology Modeling
Use a homology modeling tool such as:
- SWISS-MODEL (https://swissmodel.expasy.org/)
Modeling the protein’s structure based on sequence and available templates.

---

### 4. Model the Protein Using AlphaFold
AlphaFold (https://alphafold.ebi.ac.uk/) to generate a predicted structure for the same protein.  
Downloading the predicted model and preparing it for visualization. 

---

### 5. Visualize the Protein
Visualizing both structures using:
- PyMOL

Comparing:
- Secondary structure elements  
- Binding sites and domains  
- Structural variations between models  

---

### 6. Analyzing the Protein Structure
The **structural and functional features** of the protein:
- α-helices, β-sheets, and loops  
- Active sites and binding pockets  
- Potential implications for cancer-related pathways  

---

### 7. Evaluating Modeling Techniques
- Accuracy of each modeling technique  
- Coverage of the protein structure  
- Functional insights derived  
- Advantages and limitations of each method

## 📂 /data
| File name | Description |
|------|--------------|
| `protein_sequence.fasta` | FASTA sequence of p53 form RCSB-PDB |
| `4D1M_p53structure.pdb` | PDB structure file of p53 from RCSB-PDB |
| `Swiss_model_p53.pdb` | Structure predicted using SWISS-MODEL |
| `AlphaFold_model_p53.pdb` | Structure predicted using AlphaFold | 
| `visualization_screenshots/` | PyMOL screenshots |
| `report.md` | Comparative analysis and discussion | 

Conclusion on which method (Homology Modeling or AlphaFold) produced a more accurate and biologically meaningful structure.

---
