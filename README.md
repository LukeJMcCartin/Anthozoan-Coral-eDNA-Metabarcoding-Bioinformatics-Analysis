# Anthozoan-Coral-eDNA-Metabarcoding-Bioinformatics-Analysis

Code and reference barcode training set files associated with McCartin et al. 2024 "Nuclear eDNA Metabarcoding Primers for Anthozoan Coral Biodiversity Assessment" for the analysis of eDNA metabarcoding data generated using the 28S PCR primers. The reference database and training sets were updated in September 2025 to include new sequences of corals collected offshore Puerto Rico.

"anth_coral_references_20240915.fasta" contains the reference DNA barcodes for anthozoan coral 28S. The header lines include the taxonomy of the sequence and it's identification (e.g. GenBank Accession ID#).

"anth_coral_references_20240915_formatted_for_assignTax.fasta" contains the reference DNA barcodes, but contains only their taxonomy and is formatted as a custom training set for the [RDP naïve Bayesian classifier implemented in DADA2](https://benjjneb.github.io/dada2/training.html).

The RMarkdown file ("Anthozoan_eDNA_metabarcoding_analysis_20250918.Rmd") includes both R and zsh code chunks for the analysis of metabarcoding data generated using the 28S primers.
