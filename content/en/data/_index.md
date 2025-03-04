---
title: Data
description: Data
showHeader: false

---

## Data

{{< columns count=2 >}}
{{< column >}}
{{< img src="Data-1.png" >}}
{{< /column >}}
{{< column >}}
{{< intro >}}
The Human Pangenome Reference Consortium generates raw sequencing data, high-quality assemblies, and pangenomes. All data generated is open, publicly accessible, and can be downloaded or used in AWS, GCP, AnVIL, or locally.
{{< /intro >}}
{{< /column >}}
{{< /columns >}}

We have two “hot off the presses” data sets available at the links below for the HPRC project. These data sets are both using cutting edge technologies for evaluation for future mainstream use. A PacBio Revio sequence run performed at PacBio using an HPRC style library provided by Washington University (large discreet size fraction aiming for ~20kb), as well as an Oxford Nanopore duplex read data set generated at UCSC in close collaboration with Oxford Nanopore.

{{< columns count=2 >}}
{{< column >}}
[Revio data is now available for HG002!](https://human-pangenomics.s3.amazonaws.com/index.html?prefix=submissions/80d00e88-7a92-46d8-88c7-48f1486e11ed--HG002_PACBIO_REVIO/)
The data was generated at PacBio using HG002 libraries created at Washington University. The data set has a large, tight size fraction targeting 20kb.
{{< /column >}}
{{< column >}}
{{< img src="Data-logo-pacbio.svg" >}}
{{< /column >}}
{{< /columns >}}

{{< columns count=2 >}}
{{< column >}}
[ONT duplex data for HG002 is now available!](https://human-pangenomics.s3.amazonaws.com/index.html?prefix=submissions/0CB931D5-AE0C-4187-8BD8-B3A9C9BFDADE--UCSC_HG002_R1041_Duplex_Dorado/Dorado_v0.1.1/)
The HPRC has publicly released a dataset for Oxford Nanopore's new Duplex technology with >70X data with excellent quality (~Q29) and read length (35kbp N50) for HG002.
{{< /column >}}
{{< column >}}
{{< img src="ONT-logo.png" >}}
{{< /column >}}
{{< /columns >}}

### Data Availability

**Sequencing data, assemblies, and pangenomes are stored in publicly accesible cloud buckets, the AnVIL data ecosystem, and in SRA/ENA/DDBJ.**

* Data is uploaded to both AWS S3 and Google Cloud buckets. GitHub repositories have been created and include details about the data generation as well as index files with locations of the data stored in S3 and GCP. The HPRC S3 bucket does not charge egress fees making it a good option if you would like to download data to your local machine.
* AnVIL is a cloud environment that allows you to view the data organized in convenient data tables that refer to copies of the data in GCP. AnVIL also includes a workflow runner so you can analyze the data withough.
* All data is also uploaded to INSDCs (SRA/ENA/DDBJ) in BioProjects for sequencing data, assemblies, and pangenomes.

<div class="data-container">

{{< columns count=2 >}}
{{< column >}}

### Data Sequencing

* PacBio HiFi
* Oxford Nanopore
* Omni-C/Hi-C

In addition, we include high coverage Illumina data produced by the NYGC for parents and children (when available). If you would like to download the files, data indexes are available in the GitHub repository.
{{< /column >}}
{{< column >}}
[!['AnVil Logo'](Data-AnVil.png 'AnVil Logo')](https://anvil.terra.bio/)
[!['GitHub Logo'](Data-Github.png 'GitHub Logo')](https://github.com/human-pangenomics/HPP_Year1_Data_Freeze_v1.0)
[!['NCBI Logo'](Data-NCBI.png 'NCBI Logo')](https://www.ncbi.nlm.nih.gov/bioproject/730823)
{{< /column >}}
{{< /columns >}}

{{< columns count=2 >}}
{{< column >}}
[!['AnVil Logo'](Data-AnVil.png 'AnVil Logo')](https://anvil.terra.bio/)
[!['NCBI Logo'](Data-NCBI.png 'NCBI Logo')](https://www.ncbi.nlm.nih.gov/bioproject/730823)
[!['UCSC Logo'](Data-UCSC.png 'UCSC Logo')](http://hprc-browser.ucsc.edu/)
[!['Ensembl Logo'](Data-ensembl.png 'Ensembl Logo')](https://projects.ensembl.org/hprc/)
[!['GitHub Logo'](Data-Github.png 'GitHub Logo')](https://github.com/human-pangenomics/HPP_Year1_Data_Freeze_v1.0)
{{< /column >}}
{{< column >}}

### Assemblies

Assemblies produced with Hifiasm are available alongside annotations for the assemblies. If you would like to download the files, data indexes are available in the GitHub repository.
{{< /column >}}
{{< /columns >}}

{{< columns count=2 >}}
{{< column >}}

### Pangenomes

The HPRC has released pangenomes from its year 1 data. Currently there are three main approaches:

* Minigraph
* Minigraph-CACTUS
* Pangenome Graph Builder (PGGB)
 
Each pangenome has different strengths and weaknessness. If you do not know which pangenome best suits your needs, see the GitHub repository.
{{< /column >}}
{{< column >}}
[!['AnVil Logo'](Data-AnVil.png 'AnVil Logo')](https://anvil.terra.bio/)
[!['GitHub Logo'](Data-Github.png 'GitHub Logo')](https://github.com/human-pangenomics/hpp_pangenome_resources)
[!['ENA Logo'](Data-ENA.png 'ENA Logo')](https://www.ebi.ac.uk/ena/browser/)
{{< /column >}}
{{< /columns >}}

</div>
