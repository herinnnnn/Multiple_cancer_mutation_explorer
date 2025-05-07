# Multiple_cancer_mutation_explorer
This project aims to explore the mutations across five different types of Cancer to gain differential and overlapping insights.
---

## 🔍 Overview

This project analyzes mutation data from **cBioPortal** (TCGA studies) using Python and visualizes:
- Top mutated genes in each cancer
- Most common mutation types
- Shared vs. unique genes across cancers
- Heatmaps of gene-sample distributions
- Cross-cancer comparisons

Search the cBioPortal with each disease -> explore more studies -> download original data -> select data_mutations.txt file for each

Developed entirely in Google Colab using **pandas**, **matplotlib**, **seaborn**, and **upsetplot**.

---

## 🧪 Cancer Types Analyzed

| Acronym | Cancer Type |
|--------|--------------|
| BRCA   | Breast Invasive Carcinoma |
| LUAD   | Lung Adenocarcinoma |
| UCS    | Uterine Carcinosarcoma |
| PRAD   | Prostate Adenocarcinoma |
| COADREAD | Colorectal Adenocarcinoma |

---

## 📊 Key Results & Insights

- **Missense mutations** were the most common type across all cancers.
- **TP53** was the only gene mutated across all five cancers, acting as a universal tumor suppressor.
- **TTN** appeared in the top 5 mutated genes in 4/5 cancers, especially in LUAD and COADREAD.
- **BRCA1/2 mutations** were specific to BRCA, aligning with known clinical genetics.
- **COADREAD** had the highest mutation diversity (14,947 unique genes), while **UCS** had the fewest (1,695).
- Only **5,100 genes were shared** across all five cancers.

---


