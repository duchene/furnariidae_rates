## Welcome to the companion repository for the manuscript entitled *Flight demand and environmental niche are associated with molecular evolutionary rates in a large avian radiation*
### by David A. Duchene, Paola A. Montoya, Santiago Claramunt, and Carlos D. Cadena.

This respository contains the DNA sequence alignments used in this study for each of the mitochondrial (*mitochondrial_dna.fasta*) and nuclear (*nuclear_dna.fasta*) data.

In addition, the repository contains a data file that can be read into R using the "load" function (*pgls_data.Rdata*). Use the following code in R to load the data:

```coffee
library(caper)
load("path-to-repository/pgls_data.Rdata")
```

The following are the elements included:

#### Analyses of the association between flight habit and wing metrics

*flight.score.data* - data frame with data on the approximate flight habit score, wing loading, and hand-wing index.

*furn.tree.genera* - tree of genera of furnariidae extracted from the original phylogenetic study of the phylogenetics and diversification of furnariidae (Derryberry et al. 2011, *Evolution*, 65(10), 2973-2986).

*models.flight.score* - list containing two pgls regression objects examining the association among the flight habit score and each of wing loading and hand-wing index, respectively.

#### Analyses of the association between molecular evolutionary rates and wing metrics and environmental energy

*table.mitochondrial* - the data frame with mitochondrial molecular evolutionary rate estimates, wing loading, hand-wing index, and environmental energy for each of the species for which these data were available.

*table.nuclear* - as *table.mitochondrial* but including nuclear molecular evolutionary rate estimates.

*furn.tree.mitochondrial* - the time-tree taken from the original phylogenetic study and used for regression analyses, pruned to contain the data for which mitochondrial molecular rates could be estamated with confidence.

*furn.tree.nuclear* - as *furn.tree.mitochondrial* but including the taxa for which nuclear molecular rates could be estimated with confidence.

*models.wl* - list containing two elements for each of mitochondiral data and nuclear data. In each, three pgls regression models can be found, one for each of *dN*, *dS*, and *dN/dS*. All models include wing loading in the explanatory variables.

*models.hwi* - as *models.wl* but including the hand-wing index in the explanatory variables.

For enquiries contact David A. Duchene (david.duchene@anu.edu.au; david.duchene@sund.ku.dk).