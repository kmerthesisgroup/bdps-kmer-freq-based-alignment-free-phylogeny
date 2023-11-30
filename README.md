# A Birth-Death-Migration Model for Alignment FreePhylogeny Estimation using k-mer Frequencies

Estimating phylogenetic trees from molecular data is an important challenge in bioinformatics and
evolutionary biology. A widely used approach is to first perform a multiple sequence alignment and
then to find a tree that maximizes likelihood computed under a model of nucleotide substitution.
However, sequence alignment is computationally challenging for long sequences, especially in the presence
of genomic rearrangements. To address this, methods of constructing phylogenetic trees without aligning
the sequences i.e. alignment free methods have been proposed. They are generally fast and can be used
to construct phylogenetic trees of a large number of species but they primarily estimate phylogenies by
computing pairwise distances and are not based on any statistical model of molecular evolution. In this
paper, we introduce a model for k-mer frequency change based on a birth-death-migration process which
can be used to estimate maximum likelihood phylogenies from k-mer frequencies in an alignment free
approach.
