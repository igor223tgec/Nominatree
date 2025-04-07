# Nominatree
A simple script made to add taxa from a FASTA sequence header to a phylogenetic tree in which had only accession codes.
The progam was made in Python program language and will only work in Linux system command line due the commands that it utilizes.

To use the program, set the command:

nominatree.py [tree file] [fasta file]

The tree file is a phylogenetic with accession codes as labels. The FASTA file is the file that provided sequences to the phylogenetic tree formulation.
For the sequence ">YP_003289293.1 RNA-dependent RNA polymerase [Drosophila totivirus 1]" in the FASTA file. If the tree file has YP_003289293.1 as label, after nominatree run, it will be replaced to "YP_003289293.1 - [Drosophila totivirus 1]". The content between brackets will join to accession code.
