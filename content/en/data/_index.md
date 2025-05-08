---
title: Data
description: Data
showHeader: false

---

## Data

The Human Pangenome Reference Consortium generates raw sequencing data, high-quality assemblies and, for Data Release 1, pangenomes. All data are open and publicly accessible. Sequencing data and assemblies for Data Release 2 can be accessed through the [HPRC Data Explorer](https://data.humanpangenome.org/), or through [AnVIL](https://anvilproject.org/) and [GitHub](https://github.com/human-pangenomics/hprc_intermediate_assembly/). Data Release 2 resources are being progressively added. Where Release 2 versions are not yet available, we advise using Data Release 1, accessible through the links below. Please refer to the [HPRC Data Use Best Practices](https://humanpangenome.org/data-use/) when using HPRC data.  

<div style="text-align: center">
{{< button link="https://data.humanpangenome.org/" style="secondary" text="HPRC Data Explorer" >}}
</div>

<!-- We have two “hot off the presses” data sets available at the links below for the HPRC project. These data sets are both using cutting edge technologies for evaluation for future mainstream use. A PacBio Revio sequence run performed at PacBio using an HPRC style library provided by Washington University (large discreet size fraction aiming for ~20kb), as well as an Oxford Nanopore duplex read data set generated at UCSC in close collaboration with Oxford Nanopore.

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
{{< /columns >}} -->

### Data Availability

**Sequencing data, assemblies, and pangenomes are stored in publicly accesible cloud buckets, the AnVIL data ecosystem, and in SRA/ENA/DDBJ.**

* Data is uploaded to both AWS S3 and Google Cloud buckets. GitHub repositories have been created and include details about the data generation as well as index files with locations of the data stored in S3 and GCP. The HPRC S3 bucket does not charge egress fees making it a good option if you would like to download data to your local machine.
* AnVIL is a cloud environment that allows you to view the data organized in convenient data tables that refer to copies of the data in GCP. AnVIL also includes a workflow runner so you can analyze the data withough.
* All data is also uploaded to INSDCs (SRA/ENA/DDBJ) in BioProjects for sequencing data, assemblies, and pangenomes.

<div class="data-container">

{{< columns count=2 >}}
{{< column >}}

### Sequencing Data Release2

* PacBio HiFi (with modification calls)
* PacBio Kinnex
* Oxford Nanopore Ultralong (with modification calls)
* Dovetail
* Omni-C/Hi-C

In addition, we include high coverage Illumina data produced by the NYGC for parents and children (when available). If you would like to download the files, data indexes are available in the GitHub repository.
{{< /column >}}
{{< column >}}
[!['AnVil Logo'](Data-AnVil.png 'AnVil Logo')](https://anvil.terra.bio/)
[!['GitHub Logo'](Data-Github.png 'GitHub Logo')](https://github.com/human-pangenomics/hprc_intermediate_assembly/tree/main/data_tables/sequencing_data)
[!['NCBI Logo'](Data-NCBI.png 'NCBI Logo')](https://www.ncbi.nlm.nih.gov/bioproject/730823)
{{< /column >}}
{{< /columns >}}
<hr />
{{< columns count=2 >}}
{{< column >}}
### Assemblies Release2

Assemblies produced with Hifiasm are available alongside annotations for the assemblies. If you would like to download the files, data indexes are available in the GitHub repository.
{{< /column >}}

{{< column >}}
[!['AnVil Logo'](Data-AnVil.png 'AnVil Logo')](https://anvil.terra.bio/)
[!['NCBI Logo'](Data-NCBI.png 'NCBI Logo')](https://www.ncbi.nlm.nih.gov/bioproject/730823)
[!['UCSC Logo'](Data-UCSC.png 'UCSC Logo')](http://hprc-browser.ucsc.edu/)
[!['Ensembl Logo'](Data-ensembl.png 'Ensembl Logo')](https://projects.ensembl.org/hprc/)
[!['GitHub Logo'](Data-Github.png 'GitHub Logo')](https://github.com/human-pangenomics/hprc_intermediate_assembly/tree/main/data_tables)
{{< /column >}}
{{< /columns >}}
<hr />
{{< columns count=2 >}}
{{< column >}}

### Pangenomes Release1

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
