---
description: Workflows associated with version 1 of the Assay
cover: ../../../.gitbook/assets/Screen Shot 2022-02-17 at 3.03.38 PM.png
coverY: 0
---

# Workflows V1

## BAM Generation & Quality Control

![Overview of the BAM Generation and Quality Control workflow](<../../../.gitbook/assets/Screen Shot 2022-02-16 at 1.21.11 PM.png>)

Github Location -> [https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/ACCESS\_pipeline.cwl](https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/ACCESS\_pipeline.cwl)

Tools Used:

* [BWA](https://github.com/lh3/bwa)
* [Trimgalore](https://github.com/FelixKrueger/TrimGalore)
* [GATK](https://gatk.broadinstitute.org/hc/en-us)
* [Picard Tools](https://broadinstitute.github.io/picard/)
* [ABRA2](https://github.com/mozack/abra2)
* [Marianas](https://cmo-ci.gitbook.io/marianas/)

## Variant Calling

![BAM files used for the workflows](<../../../.gitbook/assets/Screen Shot 2022-02-16 at 1.25.02 PM.png>)

### Small Variants&#x20;

**Github Location** -> [https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/subworkflows/snps\_and\_indels.cwl](https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/subworkflows/snps\_and\_indels.cwl)

**Tools Used:**

* [VardictJava](https://github.com/AstraZeneca-NGS/VarDictJava)
* [MuTect](https://software.broadinstitute.org/cancer/cga/mutect)
* [VCF2MAF](https://github.com/mskcc/vcf2maf)

### Copy Number Variant (CNV)

**Github Location** -> [https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/subworkflows/call\_cnv.cwl](https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/subworkflows/call\_cnv.cwl)

Refer to **Bioinformatics Pipeline to Detect CNA's** section **** in this paper for details:&#x20;

[Dara S. Ross, Ahmet Zehir, Donavan T. Cheng, Ryma Benayed, Khedoudja Nafa, Jaclyn F. Hechtman, Yelena Y. Janjigian, Britta Weigelt, Pedram Razavi, David M. Hyman, José Baselga, Michael F. Berger, Marc Ladanyi, Maria E. Arcila, Next-Generation Assessment of Human Epidermal Growth Factor Receptor 2 (ERBB2) Amplification Status: Clinical Validation in the Context of a Hybrid Capture-Based, Comprehensive Solid Tumor Genomic Profiling Assay, The Journal of Molecular Diagnostics, Volume 19, Issue 2, 2017, Pages 244-254, ISSN 1525-1578, https://doi.org/10.1016/j.jmoldx.2016.09.010.](https://www.sciencedirect.com/science/article/pii/S1525157816302331)

### Structural Variant (SV)&#x20;

**Github Location** -> [https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/subworkflows/manta.cwl](https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/subworkflows/manta.cwl)

**Tool Used:**

* [Manta](https://github.com/Illumina/manta)
* [iAnnotateSV](https://github.com/rhshah/iAnnotateSV)

### Microsatellite Instability Status (MSI)&#x20;

Github Location -> [https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/subworkflows/msi.cwl](https://github.com/mskcc/ACCESS-Pipeline/blob/master/workflows/subworkflows/msi.cwl)

**Tool Used:**

* [ADMIE](https://github.com/mskcc/ADMIE)

## Configurations

Voyager has all our configurations in the jinja template, it includes all the paths for various files and tools associated with the workflows, all location are on JUNO:

#### snps\_indels: [beagle/input\_template.json.jinja2 at master · mskcc/beagle (github.com)](https://github.com/mskcc/beagle/blob/master/runner/operator/access/v1\_0\_0/snps\_and\_indels/input\_template.json.jinja2)

#### CNV: [beagle/input\_template.json.jinja2 at master · mskcc/beagle (github.com)](https://github.com/mskcc/beagle/blob/master/runner/operator/access/v1\_0\_0/cnv/input\_template.json.jinja2)

#### Fastq\_to\_bam: [beagle/input\_template.json.jinja2 at master · mskcc/beagle (github.com)](https://github.com/mskcc/beagle/blob/master/runner/operator/access/v1\_0\_0/fastq\_to\_bam/input\_template.json.jinja2)

#### MSI: [beagle/input\_template.json.jinja2 at master · mskcc/beagle (github.com)](https://github.com/mskcc/beagle/blob/master/runner/operator/access/v1\_0\_0/msi/input\_template.json.jinja2)

#### SV : [beagle/input\_template.json.jinja2 at master · mskcc/beagle (github.com)](https://github.com/mskcc/beagle/blob/master/runner/operator/access/v1\_0\_0/structural\_variants/input\_template.json.jinja2)
