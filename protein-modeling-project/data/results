# Protein Structure Alignment and RMSD Analysis

This repository contains the structural comparison of **p53 protein** using:

- **Experimental PDB structure**: `4D1M`  
- **Predicted models**:
  - AlphaFold prediction (`AlphaFold_model_p53`)
  - SWISS-MODEL prediction (`Swiss_model_p53`)

All alignments and RMSD calculations were performed using **PyMOL**.  

---

## 1. Alignment: Experimental vs AlphaFold

**Structures:**

- Model 1: 4D1M_p53structure (green)  
- Model 2: AlphaFold_model_p53 (cyan)

**RMSD:** `1.268 Å` (275 atoms aligned)

**Observation:**

- The AlphaFold predicted structure closely matches the experimental structure, with RMSD < 2 Å.  

**Visualization:**

![Alignment_Model_1&2](results/Alignment_Model_1&2.png)

---

## 2. Alignment: Experimental vs SWISS-MODEL

**Structures:**

- Model 1: 4D1M_p53structure (green)  
- Model 3: Swiss_model_p53 (magenta)

**RMSD:** `0.078 Å` (1151 atoms aligned)

**Observation:**

- SWISS-MODEL shows an excellent alignment with the experimental structure.  
- This is likely because the homology model used templates from experimentally solved structures, resulting in highly accurate modeling.  
- RMSD is almost negligible, indicating near-perfect overlap.

**Visualization:**

![Alignment_Model_1&3](results/Alignment_Model_1&3.png)

---

## 3. Conclusion

- Both **SWISS-MODEL** and **AlphaFold** produced high-quality models of p53.  
- SWISS-MODEL achieved almost perfect alignment due to template-based modeling.  
- AlphaFold RMSD < 2 Å confirms its prediction is still very reliable.  
- These results validate that predicted SWISS-MODEL can be confidently used for structural analysis, mutational studies, or drug-target interaction modeling.

---
