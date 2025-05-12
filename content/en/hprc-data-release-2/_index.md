---
title: HPRC Data Release 2
description: HPRC Data Release 2
showHeader: false

---

## HPRC Data Release 2

**Announcing the Human Pangenome Reference Consortium Data Release 2**

May 12, 2025

We are excited to announce the second data release (Release 2\) of the Human Pangenome Reference Consortium (HPRC) in pre-publication form. Release 2 includes sequencing data and high-quality phased genomes from over 200 individuals, a nearly fivefold increase over [Release 1](https://www.nature.com/articles/s41586-023-05896-x). This open-access release represents a substantial step forward in our effort to build a more complete, accurate, and representative human pangenome reference. It is also the first release to incorporate samples sequenced and assembled by international partners, including collaborators at the University of Tokyo in Japan and the Human Technopole in Italy. In addition to the National Human Genome Research Institute (NHGRI), the project has been generously supported by company partners, including PacBio, Oxford Nanopore Technologies, Illumina, Dovetail Genomics, Google, and Amazon Web Services (AWS).

**Highlights of HPRC Release 2 Sequencing Data:**

* **Multiple Data Types:** PacBio HiFi, ONT Ultralong, Dovetail/Illumina Hi-C, PacBio Kinnex RNA, and Illumina WGS data are available for over 200 samples.  
* **High Coverage:** Samples have uniformly high sequencing coverage with 60X PacBio HiFi and 30X Oxford Nanopore over 100kb.  
* **Modern and Standardized:** All HiFi is basecalled with DeepConsensus, off-instrument for Sequel II and on-instrument for Revio. ONT R9 and R10 data were uniformly basecalled to produce consistent, high-quality reads. Both HiFi and ONT data include 5-methylcytosine predictions.

**Highlights of HPRC Release 2 Assemblies:**

* **Expanded Number of Assemblies:** Release 2 includes assemblies from an increased number of diverse individuals, significantly expanding the representation of global human genomic variation compared to Release 1\. This release incorporates genomes from a total of 232 individuals.  
* **Improved Assembly Quality:** The assemblies in Release 2 benefit from the use of advanced algorithms that integrate long-read sequencing from PacBio HiFi and ONT as well as phasing from Illumina trio-WGS or Hi-C data. This integration has resulted in significantly more continuous and structurally accurate assemblies, reducing misassemblies by approximately threefold and enabling a substantial number of complete, telomere-to-telomere chromosome assemblies.  
* **Enhanced Accuracy:** A novel deep learning based base-level assembly polishing step, developed primarily by Google Research in collaboration with the UC Santa Cruz Genomics Institute, has been incorporated into the Release 2 processing pipeline. Coupled with sequencing technology improvements, this reduces single-nucleotide and short insertion and deletion errors by a factor of two, resulting in an estimated error rate of less than one base error per half a million assembled bases.

These new assemblies and the underlying sequencing data are a cornerstone of the pangenome reference, enabling researchers to better identify and interpret genetic variation, particularly in complex and repetitive regions of the genome that were previously challenging to analyze with a single linear reference. Additional resources forming the complete second release of the Human Pangenome will soon follow, including:

* **Comprehensive Annotations:** Accompanying the assemblies will be detailed annotations, including gene annotations that integrate full-length RNA isoform data (PacBio Kinnex) for most samples.  
* **Graph-Based Alignments:** Release 2 will also include graph-based assembly alignments, providing an integrated view of the pangenome and facilitating comparative analyses using pangenome tools.

**Data Access:**

All data from HPRC Release 2, including the new assemblies, is publicly available in our AWS S3 bucket as well as public nucleotide archives (INSDC). You can learn more about the data and access download links in a number of ways:

* **HPRC Data Explorer:** A new data explorer that allows users to interactively find and select sequencing data, assemblies, annotations, and alignments for download is available at: [https://data.humanpangenome.org/](https://data.humanpangenome.org/)  
* **HPRC GitHub:** Sequencing data, assemblies, and assembly annotations are documented in our Release 2 GitHub repository. Index files with metadata and S3 locations and SRA/Genbank accessions are included for each data type, allowing bulk downloads.  
  * [Sequencing Data](https://github.com/human-pangenomics/hprc_intermediate_assembly/tree/main/data_tables/sequencing_data)
  * [Assemblies](https://github.com/human-pangenomics/hprc_intermediate_assembly/tree/main/data_tables)
  * [Assembly Annotations](https://github.com/human-pangenomics/hprc_intermediate_assembly/tree/main/data_tables)
* **AnVIL:** The data will shortly be available from the [AnVIL cloud environment](https://anvilproject.org/).  
* **INSDC**: You can download HPRC genomes submitted to INSDC as a [customized data package](https://www.ncbi.nlm.nih.gov/datasets/genome/?bioproject=PRJNA730822) through web or command line interfaces. Explore additional HPRC-related content, including publications, through the [BioProject](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA730822/).

We encourage the community to explore and utilize this valuable resource to advance our understanding of human genetic variation and its impact on health and disease. For scientists interested in publishing using this pre-publication data, please see our consortium [publication policy](https://humanpangenome.org/publication-policy/) and [best practices for using](https://humanpangenome.org/data-use/) the data.
