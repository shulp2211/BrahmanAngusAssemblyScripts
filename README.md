# Brahman and Angus Assembly Scripts
This repository contains custom scripts to analyse scaffolds and validate genome assemblies of Angus and Brahman cattles. The novel contig assembly approach that generated haplotype-resolved contigs was published elsewhere by [Koren et al (2018)](https://www.nature.com/articles/nbt.4277) and this step will not be detailed here. The work described here followed up from the contigs assemblies to generate haplotype-resolved chromosome-level scaffolds. It also contains some scripts used for specific analyses that involved SNPs, indels, and various types of structural variants (SVs).

## Table of contents
All scripts are given in the scripts directory. Specific scripts and datasets for the various assembly stages are given or listed in directories below in this repository
* scaffolding_with_optical_map_and_HiC
* sex_chromosomes_assemblies_and_validation
* comparison_of_gaps
* QV_estimation
* SV_analyses
* selective_sweep
* phasing_transcripts

Here is a brief description of the contents of each directory.

### scaffolding with optical map and HiC
This folder contains information on how optical map based scaffolds and Hi-C based scaffolds were analysed together with recombination map markers to produce the final validated scaffolds.

### sex chromosomes assemblies and validation
Here are the specific scripts and information used to put together the sex chromosomes, which was more challenging given the higher number of gaps. The assemblies utilized different sources of linkage and radiation hybrid (RH) markers to guide order and orientation of the contigs that belong to Brahman X and Angus Y chromosomes.

### comparison of gaps
This folder has the raw datasets of gap and ungapped contigs lengths as well as the R scrips used for analysis.

### QV estimation
Here are the results by Derek Bickhart on QV estimation of the Angus and Brahman assemblies. The folder contains notes on software requirements and how to run the QV estimation.

### SV analyses
This folder details the comparison of SV between Brahman and Angus assemblies.

### selective sweep
This folder details the selective sweep analysis after obtaining SNPs called from GATK and annotated with Annovar.

### phasing transcripts
The phasing of transcripts using isoseq3 and IsoPhase is described in this folder.
