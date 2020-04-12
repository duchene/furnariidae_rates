## Welcome to the companion repository for the manuscript entitled *Wing shape and environmental energy niche breadth are associated with molecular evolutionary rates in a large avian radiation*
### by David A. Duchene, Paola A. Montoya, and Carlos D. Cadena.

This respository contains the molecular data alignments used in this study. Specifically, the data sets include the mitochondrial (*mitochondrial_data.fasta*), nuclear (*nuclear_data.fasta*), and combined data sets (*combined_data.fasta*).

In addition, the repository contains a data file to be read in R using the "load" function (*data_tables_and_trees.Rdata*). The elements found in this file are the following:

*table_mitochondrial* - the data frame with mitochondrial molecular evolutionary rate estimates, hand-wing index, and environmental energy for each of the species for which these data were available

*table_nuclear* - as table_mitochondrial but including nuclear molecular evolutionary rate estimates

*table_overall_rates* - as table_mitochondrial but including the molecular evolutionary rate estimates including all the molecular data available

*tree_mitochondrial_taxa* - the time-tree used for regression analyses as estimated in the original phylogenetic study of the phylogenetics and diversification of furnariidae (Derryberry et al. 2011, Evolution, 65(10), 2973-2986). The tree was pruned to contain the data for which mitochondrial molecular evolutionary rates could be estamated with confidence

*tree_nuclear_taxa* - as tree_mitochondrial_taxa but including the taxa for which nuclear molecular evolutionary rates could be estimated with confidence
