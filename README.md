# Pan-genome architecture and antimicrobial resistance profiling of Corynebacterium striatum

## Overview

This repository contains fully reproducible Python workflows supporting the large-scale pan-genome analysis of 839 Corynebacterium striatum genomes, with a specific focus on antimicrobial resistance (AMR) gene distribution and functional compartmentalization.

The study characterizes core, shell, and cloud genome compartments and investigates the localization of resistance determinants across the pan-genome landscape. Functional enrichment analyses based on eggNOG annotations were performed to assess adaptive and conserved genomic features.

All scripts required to reproduce the computational analyses and manuscript figures are provided.

---

## Study Design

- Total genomes analyzed: 839 publicly available C. striatum assemblies
- Pan-genome matrix derived from annotated genomes
- Genome compartments defined by gene frequency thresholds
- AMR genes identified using AMRFinderPlus
- Functional annotations obtained via eggNOG-mapper
- Statistical analyses and visualization performed in Python

---

## Repository Structure

data/
    raw/            # Genome accession lists and minimal input files
    processed/      # Cleaned presence/absence matrices and merged annotations

metadata/           # Genome metadata and compartment classification tables

scripts/            # Python scripts for analysis and figure generation (numbered pipeline)

results/            # Summary tables and statistical outputs

figures/            # Final manuscript-ready figures

supplementary/      # Supplementary figures and extended tables

---

## Analysis Workflow

1. Data cleaning and preparation of pan-genome matrix
2. Assignment of genes to core, shell, and cloud compartments
3. Integration of AMR gene annotations
4. Functional enrichment analysis (COG categories)
5. Statistical evaluation of compartmental distribution
6. Generation of publication-quality figures

Scripts are sequentially numbered to allow step-by-step reproduction.

---

## Requirements

Python ≥ 3.9

Required packages:
- pandas
- numpy
- matplotlib
- scipy
- seaborn
- scikit-learn

Install dependencies using:

pip install -r requirements.txt

---

## Reproducibility

Clone the repository:

git clone https://github.com/<username>/<repository-name>.git

Navigate to the repository directory and execute scripts sequentially from the `scripts/` folder.

All analyses are performed using relative file paths to ensure portability.

---

## Citation

If you use this repository or its code, please cite the associated manuscript: (in progress)


---

## Contact

For questions regarding the analysis, please contact:
Umama Shahid
umamashahid148@gmail.com
