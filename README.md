# ImmuneRemodellingECM
These are scripts that were used to make the figures in the paper:

An Effective Anti-Tumour T Cell Response Remodels the Tumour Microenvironment Amplifying Immunity and Facilitating Loss of Tumour Initiating Cells.

Pires et al 2020

The scripts deal with two areas:

Analyis of microarray data from murine fibrosarcoma tumours in mice which respond and do not respond to depletion of regulatory T cells.
1. Comparison using Limma to find differentially expressed genes (DEGs).
2. Pathway analysis with Reactome on the sets of DEGs.
3. Manhattan distance analysis to look for genes with most similar and most different (normalised) gene expression patterns to the gene of interest.

Analysis of TCGA data in 21 cancers to look at survival based on the expression of a gene or gene signature.
1. Cancers (primary tumours only, duplicates or more removed) each are clustered into two groups (high and low) based on expression of a CTL gene signature.
2. Each sub group is then clustered into two more groups based on expression of an ECM gene.
3. Survival is analysed across the groups.

TCGA data can be downloaded from the GDC portal for the cancers specified (see code or manuscript).
Microarray raw and normalised data can found at array express, accession number:
E-MTAB-9351


Post any code questions or requests here in issues please.
