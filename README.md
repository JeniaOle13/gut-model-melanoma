# Gut Microbiome Modulation in Model Melanoma-Bearing Mice by Probiotic Intervention

## Overview

This repository hosts the complete bioinformatics workflow and analytical results for our study investigating how probiotic supplementation with *Bifidobacterium adolescentis* 150 and *Lacticaseibacillus rhamnosus* K32 modulates gut microbiome composition in B16-F1 melanoma-bearing mice. Utilizing Oxford Nanopore full length 16S rRNA gene sequencing, we characterize microbial community changes and identify potential probiotic-mediated shifts associated with tumor progression.

🔗 **Access the full study report:** [https://jeniaole13.github.io/gut-model-melanoma/](https://jeniaole13.github.io/gut-model-melanoma/)

## Key findings
- *B. adolescentis* 150 accelerated tumor growth, linked to *Klebsiella* enrichment.
- *L. rhamnosus* K32 increased *Klebsiella* abundance and reduced microbiome diversity, yet had no significant impact on tumor progression.

## Repository structure
```
data/                      
├── maaslin2-1.tsv          # Maaslin2 results #1 (with M as reference)
├── maaslin2-2.tsv          # Maaslin2 results #2 (with M_LAC as reference)
├── metadata.tsv            # 16S rRNA samples metadata
├── otu_table.tsv           # Genus abundance table 
├── statistic.tsv           # Quality control statistic
├── taxonomy.tsv            # Taxonomy table
└── tumor.tsv               # Tumor growth data
figures/                    # Figures for Quarto report
gut-microbiome-report_files # Files for Quarto report
README.md                   # repository description file
gut-microbiome-report.html  # Quarto HTML file
gut-microbiome-report.qmd   # Quarto qmd file
```

## Data Availability
Raw sequencing data is available uned BioProject [PRJNA1214537](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1214537/).

## Contacts
For any questions regarding this work, please contact us at jeniaole01@gmail.com

## Funding
Financial support for this study was provided by the Russian Science Foundation under the grant #22-75-10029 (https://rscf.ru/project/22-75-10029/).
