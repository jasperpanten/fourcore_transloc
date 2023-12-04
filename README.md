## Four-Core Genotypes mice harbour a 3.2MB X-Y translocation that perturbs Tlr7 dosage

This repository contains all code to reproduce the results from the 4CG translocation preprint. 

## Data availability

All data is available at ArrayExpress under the accession numbers E-MTAB-13585 (whole genome sequencing data),
E-MTAB-13586 (scRNA-Seq of splenocytes) and XXX (snRNA-Seq data of liver).
This includes raw read files, and per cell expression quantifications and filtered count matrices with cell type annotations.

## WGS data
The whole_genome_seq folder contains a snakemake workflow for alignment and deduplication. Furthermore, it contains a
script containing code to generate coverage quantifications including allele-specific signals and code to generate all
figures.

## scRNA-Seq of splenocytes
The sc_rna_seq folder contains a snakemake workflow for cellranger-based alignment, and r scripts to assemble, filter
and annotate the datasets. In the analysis folder, there are scripts to perform differential expression analysis and
generated the plots in the main figures, as well as code to generated all supplementary figures.

## snRNA-Seq of liver cells
The preprocessing of sci-rnaseq on liver cells was done using the sci-rocket pipeline
(https://github.com/odomlab2/sci-rocket/tree/main).

## Contact
Jasper Panten (j.panten@dkfz-heidelberg.de)
