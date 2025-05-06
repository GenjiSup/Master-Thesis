Yeast GxE Analysis – TRIUMPH Project (Master’s Thesis)


This repository contains the scripts and supporting files used in the analysis conducted for my master’s thesis, which forms part of the larger TRIUMPH project. The goal of this work is to better understand genotype-by-environment (GxE) interactions in Saccharomyces cerevisiae by identifying strains, variants, and gene targets that influence metabolic function under different environmental conditions.

The project is structured around two main research objectives:

R1 – Strain and Variant Selection
The first objective focuses on selecting suitable yeast strains for genome editing based on variant overlap and consistency between two sequencing datasets. One dataset is the publicly available Canonical Reference Genome (CRG) from Bloom et al., and the other is newly generated whole genome sequencing (WGS) data from the same strains grown under controlled conditions. Variant overlap and consistency across different alignment tools (BWA and Bowtie2) were evaluated to identify robust candidate strains and variants.

R2 – Gene List Expansion
The second objective involves expanding an existing list of mitochondrial and metabolic genes by incorporating additional targets derived from transcriptomic analysis. Differential expression analysis (DEA) and gene set enrichment analysis (GSEA) were performed on a pan-transcriptomic RNA-seq dataset from Caudal et al., covering over 900 natural yeast isolates. The focus was on identifying genes with consistent expression shifts across ecological origins, particularly those involved in fermentation and ethanol metabolism.

Repository Structure

01_variant_overlap_analysis/
Scripts used to compare variant overlap between CRG and laboratory WGS datasets, using both BWA and Bowtie2 alignments.

02_gene_list_extension/
Contains code for processing the RNA-seq dataset, performing differential expression analysis (DEA), and running gene set enrichment analysis (GSEA).

03_data_visualization/
Plots used in the thesis.

References
Bloom, J. S. et al. Rare variants contribute disproportionately to quantitative trait variation in yeast. Elife 8, (2019).
Caudal, E. et al. Pan-transcriptome reveals a large accessory genome contribution to gene expression variation in yeast. Preprint at https://doi.org/10.1101/2023.05.17.541122 (2023).

