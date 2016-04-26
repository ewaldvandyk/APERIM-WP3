# APERIM-WP3
Pipeline for Immunogenicity prediction

A pipeline adding freatures that will eventually help in predicting immunogenicity.
Features include:
1) IO - Pipeline for reading and writing .csv files with defined columns 
2) Calis immunogenicity score
3) Calis self similarity score
  3.1) Extracting netChop CTerm3 scores for any given proteome in fasta format
  3.2) Extracting netMHCpan nM affinity for any given proteomme in fasta format and any give peptide length
  3.3) Filtering peptides in any given proteome based on netChop and affinity thersholding
