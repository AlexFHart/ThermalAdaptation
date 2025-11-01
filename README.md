# ThermalAdaptation

This is the set of scripts which comprise a pipeline from raw sequence data to gene expression analyses for an experiment on Callosobruchus maculatus adaptation to temperature extremes. 

1. Initial stats via FastQC
2. Read trimming and filtering with Trimmomatic
3. HiSat2 reference genome index generation and subsequence read alignment to reference
4. SAMtools processing to sort the mapped reads by co-ordinates, filter unmapped reads, and produce indexes for each library
5. HTSeq count to count the number of reads at each genomic feature
6. Gene whitelist generation via EdgeR
7. General gene expression analysis via EdgeR
8. Gene Ontology analysis
9. Statistical analaysis approaches using Fisher's Exact tests etc.
10. WGCNA & Circlize visualisation
11. Upset plots, Venn diagrams, and other visualisation tools
