# Cellular heterogeneity in the developing forebrain masks transcriptional outcomes and principles of Evf2 enhancer lncRNA-Dlx5/6UCE-gene guidance

This code is a part of the above paper. The goal is to find the evf1-2 identities. 

The required dataset for input follows a csv format, with one column labelled "Chromosome," and one column labeled "sequence." Given a sequence length, the objective is to count the number of sequences between each chromosomes (each unique label in the column "Chromosome"). It is assumed that the initial sequences (the values in the "sequences" column) are of the same length. In this dataset, the sequences are of size 200, and the defined sequence length is 25. 

Ultimately, given the dataset "sequences.csv," this code outputs that there are 154 unique commonalities of length 25 between the chromosomes. 

Required Python packages include:
Python 3.9.7
Pandas 1.5.3
Numpy 1.23.5
