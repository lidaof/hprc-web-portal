---
title: Definitions
description: Definitions
showHeader: false

---

## Definitions

Allelic variation: Heterozygosity at a specific genomic location.

Genomic variation: Differences in DNA sequences among individuals.

Genomic diversity: The DNA variation found within a species.

Haplotype: a group of DNA variants inherited from a single parent and located on the same chromosome.

Reference genome: a low-error genome and associated annotation coordinate system that can be used as the backbone for genome alignment.

Linear genome: a linear genome represents contiguous or gapped-scaffolded genome sequences in a series of rows in a flat text file. This is the historical or traditional method for organizing genomic data. The term ‘linear genome’ should be limited to assemblies, consensus sequences, and alignment files, and should not be used to describe raw input reads.

The human reference genome: the human reference genome was created in large part during the Human Genome Project. It includes data from multiple individuals, as well as base-level corrections based on the literature, and centromeric bait sequences to improve alignments.

Pangenome: The collection of all of the genetic information of a species.

The pangenome reference: The reference pangenome is composed of all of the individual pangenome assemblies; the pangenome alignment of all of the haplotypes within those assemblies (represented as a pangenome graph); and a coordinate system to make it possible to locate sequence variants relative to the reference pangenome.

The HPRC pangenome reference: A representative subset of the human pangenome, which contains the three “A’s”: assemblies, alignments, and annotations.

Assembly: the sequence of an individual genome assembled from sequence data. In the context of a reference pangenome, high quality is imperative. The HPRC aims to achieve haplotype-resolved, telomere-to-telomere sequence assemblies for all genomes in its stable release.

Alignment: An alignment of haplotypes that delineates the similarities and differences between two or more assembled genomes. This alignment, or map, is key to finding variations and providing a comprehensive coordinate system that relates the genomes. Alignments and assemblies can be described using a pangenome graph.

Annotation: Descriptions of known functional features (e.g. genes) within a genome. These annotations can be made for each individual assembly, and also within an integrated  coordinated system (see Alignments).

Telomere to telomere (T2T): A complete, gapless genome assembly covering all base pairs and allowing the ordering of all DNA sequences into individual chromosomes.

Pangenome graph: A mathematical graph describing an alignment of a collection of genome assemblies. A pangenome graph can encode any form of genetic variation between the sequences, including copy-number variants and complex structural variations. Pangenome graphs provide a convenient formalism for computational analyses and algorithms. Different formalisms are possible, see Garrison et al. Pangenome Graphs (<https://pubmed.ncbi.nlm.nih.gov/37066137/>) for a review.

The pangenome reference resource: A pangenome reference that can be readily used by the genomics community and beyond. This includes the pangenome and its maintenance and improvement, the underlying data used to construct it, and informatics tools to enable its wide use for basic and clinical genomics research and applications. Some of these tools will be developed by the HPRC, but it is expected that over time tools and applications will also be developed by the wider community.
