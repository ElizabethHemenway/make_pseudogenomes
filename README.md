# Make a pseudogenome
Elizabeth Hemenway
09/19/2024
By "pseudogenome" in this use case we mean a FASTA genome file where we've taken the reference genome (like TAIR10/Col-0) and replaced the SNPs for the ecotype variant of your choice.

# Usage example 
using SYRI output file for C24 ecotype from Jiao et al 2020 Nature Communications (https://www.nature.com/articles/s41467-020-14779-y) and the TAIR10 reference genome (https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000001735.4/)


./make_pseudogenome.sh ./TAIR10.fa T10 C24 ./pseudoG_output/ ./path2scripts/
