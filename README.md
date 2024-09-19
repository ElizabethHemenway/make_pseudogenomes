# Make a pseudogenome
Elizabeth Hemenway - 09/19/2024

By "pseudogenome" in this use case I mean a FASTA genome file where we've taken the reference genome (like TAIR10/Col-0) and replaced the SNPs for the ecotype variant of your choice.

# Usage example 
using SYRI output file for C24 ecotype from Jiao et al 2020 Nature Communications (http://1001genomes.org/data/MPIPZ/MPIPZJiao2020/releases/current/strains/C24/)) and the TAIR10 reference genome (https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000001735.4/).


./make_pseudogenome.sh syri.out T10 C24 ./TAIR10 ./pseudoG_output/ ./path2scripts/
