---
description: Things to know for MSK-ACCESS V1 for Research
cover: ../../../.gitbook/assets/Screen Shot 2022-02-07 at 4.30.29 PM (1).png
coverY: 0
---

# MSK-ACCESS V1

### What is MSK-ACCESS?

It is a hybrid capture panel designed for **A**nalysis of **C**irculating [**c**fDNA](https://en.wikipedia.org/wiki/Circulating\_free\_DNA) to **E**valuate **S**omatic **S**tatus using the Unique Molecular Index (UMIs) for high sensitivity. MSK-ACCESS is 13% as large, captures 47% of all mutations detected by MSK-IMPACT.

[Brannon, A. R. et al. Enhanced specificity of clinical high-sensitivity tumor mutation profiling in cell- free DNA via paired normal sequencing using MSK-ACCESS. Nat Commun 12, 3770 (2021).](https://www.nature.com/articles/s41467-021-24109-5)

![Duplex UMIs for Error Correction](<../../../.gitbook/assets/Screen Shot 2022-02-16 at 1.59.24 PM.png>)

### What is the panel design?

Selected exons of 129 genes for mutation detection

* [OncoKB](https://www.oncokb.org) Level 1-4
* [Hotspot sites](https://www.cancerhotspots.org)
* High rates of mutations
* [Protein kinase domains](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/protein-kinase-domain#:\~:text=Protein%20Kinase%20Structure.%20Eukaryotic%20protein%20kinase%20domains%20segregate,site%20in%20a%20cleft%20between%20the%20lobes%20%5B12%E2%80%9315%5D.)
* [Tumor suppressor genes](https://www.cancer.org/cancer/cancer-causes/genetics/genes-and-cancer/oncogenes-tumor-suppressor-genes.html#:\~:text=Tumor%20suppressor%20genes.%20Tumor%20suppressor%20genes%20are%20normal,out%20of%20control%2C%20which%20can%20lead%20to%20cancer.)

[Microsatellite regions](https://www.thermofisher.com/blog/behindthebench/microsatellite-instability-and-mismatch-repair-in-oncology/#:\~:text=What%20are%20microsatellites%3F%20Microsatellites%20are%20highly%20polymorphic%20regions,The%20term%20was%20coined%20in%20the%20late%201980s.)

SNPs of [zygosity](https://en.wikipedia.org/wiki/Zygosity) & [copy number](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2703871/) of 12 genes

Common [SNPs](https://www.genome.gov/genetics-glossary/Single-Nucleotide-Polymorphisms) for [genome-wide copy number](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2703871/)

Introns for [structural variants](https://www.nature.com/articles/s41586-019-1913-9) of 10 genes

[Clonal hematopoiesis](https://www.science.org/doi/10.1126/science.aan4673?url\_ver=Z39.88-2003\&rfr\_id=ori:rid:crossref.org\&rfr\_dat=cr\_pub%20%200pubmed) genes

### What are the Design Implications?

* Matched cfDNA-WBC (”tumor-normal”) assay to detect somatic alterations
* Sensitivity for mutation calling depends on ‘duplex’ collapsed coverage
* Different sensitivities for different classes of alterations
  * &#x20;Genotyping  +++++
  * De novo mutations, indels  ++++
  * MSI  +++
  * Rearrangements  +++
  * Copy number  ++
  * Tumor mutation burden  ○

{% hint style="info" %}
**+** -> sensitivity for that event type

**○** -> cannot be calculated
{% endhint %}
