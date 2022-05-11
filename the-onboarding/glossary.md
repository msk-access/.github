---
description: Terms you might encounter
cover: >-
  https://images.unsplash.com/photo-1513710281312-7a43f9cdbfcc?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHwxMHx8bmFtZXxlbnwwfHx8fDE2NDQyODA2MDI&ixlib=rb-1.2.1&q=85
coverY: 0
---

# Glossary

#### [SMILE](https://github.com/mskcc/cmo-metadb) -> information associated with a sample. This is a current work-in-progress written in Java/Neo4J that is supposed to be the one source of truth for metadata associated with samples. Currently, these responsibilities are managed by Beagle.

#### LIMS -> Laboratory information management system -- when sequencing is complete, metadata and file information on the sequences is first input into this system.

#### [Beagle](https://github.com/mskcc/beagle) -> triggers and monitors workflows. There's also a part of it that tracks files and metadata associated with those files which may be splintered out in the future. A request typically comes from LIMS which begins the workflow process.

#### [Hermes ](https://github.com/mskcc/hermes)-> a nicer interface for Beagle (sample workflow tracking) and soon the MDB (make updates to metadata)

#### [Ridgeback](https://github.com/mskcc/ridgeback) -> An HTTP API for Toil which Beagle is reliant on for interacting with workflows.

#### [Toil](https://toil.readthedocs.io/en/latest/running/cwl.html) -> A workflow engine that interfaces well with LSF.

#### Voyager -> The suite of applications built by the Voyager team, including Ridgeback, Beagle, and Hermes.

#### [HPC](http://actg.mskcc.org/hpc/getting-started/)-> Distributed high-performance computing that's managed in-house. Most data processing and files are housed here.

#### [LSF](https://www.ibm.com/products/hpc-workload-management) -> IBM's Platform Computing (Load Sharing Facility) tool for scheduling workflows on HPC. It has a [suite of commands ](https://hpc.llnl.gov/banks-jobs/running-jobs/lsf-commands)specific to managing workloads.

#### [Common workflow language](https://www.commonwl.org) -> a YAML-like language for defining workflows.

#### [Nextflow](https://www.nextflow.io/docs/latest/index.html) -> Reactive workflow framework and a programming [DSL](http://en.wikipedia.org/wiki/Domain-specific\_language) that eases the writing of data-intensive computational pipelines.

#### [DNA-SEQ](https://en.wikipedia.org/wiki/DNA\_sequencing) -> Sequencing of the **Deoxyribonucleic acid (**[**DNA**](https://en.wikipedia.org/wiki/DNA)**)**

#### [RNA-SEQ](https://en.wikipedia.org/wiki/RNA-Seq) -> Sequencing of the R**ibonucleic acid (**[**RNA**](https://en.wikipedia.org/wiki/RNA)**)**

#### [MSK-ACCESS](https://www.mskcc.org/departments/division-solid-tumor-oncology/early-drug-development-service-phase-clinical-trials/precision-medicine-approach/msk-access) -> Cell-Free DNA assay for patients with solid tumors

#### **CMO-CH ->  Assay for profiling clonal hematopoiesis mutations from blood**

#### [**MSK-IMPACT**](https://www.mskcc.org/departments/division-solid-tumor-oncology/early-drug-development-service-phase-clinical-trials/precision-medicine-approach/msk-impact) **-> Assay for profiling patients tissue DNA for solid tumors**

#### ****[**MSK-IMPACT Heme**](https://aacrjournals.org/cancerres/article/79/13\_Supplement/3409/542857/Abstract-3409-MSK-IMPACT-Heme-Validation-and) **-> Assay for profiling patients blood DNA for Heme malignancies**

#### ****[**Facets**](https://pubmed.ncbi.nlm.nih.gov/27270079/) **-> A**llele-specific copy number and clonal heterogeneity analysis tool for high-throughput DNA sequencing

#### ****[**WES**](https://en.wikipedia.org/wiki/Exome\_sequencing) **-> Whole Exome Sequencing**

#### ****[**WGS**](https://www.cdc.gov/pulsenet/pathogens/wgs.html) **-> Whole Genome Sequencing**&#x20;

#### ****[**WTS**](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6233721/) **-> Whole Transcriptome Sequencing**

#### ****[**Illumina**](https://en.wikipedia.org/wiki/Illumina,\_Inc.) **-> one of the companies that provides sequencing machine**

#### ****[**Novaseq**](https://www.illumina.com/systems/sequencing-platforms/novaseq.html) **-> Type of sequencer from Illumina**

#### ****[**Nextseq**](https://www.illumina.com/systems/sequencing-platforms/nextseq-1000-2000.html) **-> Type of sequencer from Illumina**

#### ****[**Miseq**](https://www.illumina.com/systems/sequencing-platforms/miseq.html) **-> Type of sequencer from Illumina**

#### ****[**Hiseq**](https://www.illumina.com/systems/sequencing-platforms/hiseq-2500.html) **-> Type of sequencer from Illumina**

#### ****[**PacBio**](https://en.wikipedia.org/wiki/Pacific\_Biosciences) **-> a company that sells instruments for long-read sequencing based on** [**zero-mode waveguide**](https://en.wikipedia.org/wiki/Zero-mode\_waveguide)****

#### ****[**Oxford Nanopore**](https://en.wikipedia.org/wiki/Oxford\_Nanopore\_Technologies) **-> a company that sells instruments for long-read sequencing based on** [**Nanopore**](https://en.wikipedia.org/wiki/Nanopore\_sequencing) **technology**&#x20;
