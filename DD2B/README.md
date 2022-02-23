# DD2B

DD2B was designed for for taxonomic assignment in which both the RDP Classifier in DADA2 and the BLAST were used: if an amplicon sequence variants (ASVs) was not assigned at the species level (output of NA) or assigned to known indistinguishable species, including Shigella spp., Escherichia spp., Bacillus spp., by the RDP Classifier combined with a database, the sequence was BLAST-searched against the respective database for species assignment. 

## Content
### Main script
- DD2B.R : DD2B R script
- DD2B_fun.R : the subfunction 
### Curated 16S rRNA sequence databases 
BLAST database formate by makeblastdb from FASTA files






