---
cover: >-
  https://images.unsplash.com/photo-1460925895917-afdab827c52f?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHw2fHxBbmFseXNpc3xlbnwwfHx8fDE2NDQyNjM0NTU&ixlib=rb-1.2.1&q=85
coverY: -1.910236220472441
---

# Computational Biologist

{% hint style="warning" %}
<mark style="color:blue;">**Please visit this page once you have done things necessary here:**</mark> [**https://mskcc.github.io/on-boarding/**](https://mskcc.github.io/on-boarding/)****
{% endhint %}

* The best place to start is to learn more about MSK-ACCESS and for that please read the paper:
  * [Brannon, A. R. et al. Enhanced specificity of clinical high-sensitivity tumor mutation profiling in cell- free DNA via paired normal sequencing using MSK-ACCESS. Nat Commun 12, 3770 (2021).](https://www.nature.com/articles/s41467-021-24109-5)
* Learn more about the current collapsing method [Marianas](https://msk-access.gitbook.io/marianas/)
* Learn more about the new collapsing ([Nucleo](https://msk-access.gitbook.io/nucleo)) method using [Fgbio](http://fulcrumgenomics.github.io/fgbio/)
* Learn more about the [Quality Control V1](https://cmo-ci.gitbook.io/access-quality-control-v1/)
* Understand the updated version for the above using these [Quality Control V2](https://cmo-ci.gitbook.io/access-quality-control-v2/)
* Learn about [ACCESS Data analysis](https://cmo-ci.gitbook.io/access-data-analysis-v1/) scripts that help with downstream analysis
* Learn about [IGV](https://igv.org) for viewing BAM files to distinguish real variants from artifacts

{% hint style="info" %}
<mark style="color:blue;">**Below are resources that would be handy for you to learn more about all the tools described in the paper.**</mark>&#x20;
{% endhint %}

## Project Management

| Assay/Team                          | Link to the tool                                                                                                                                           |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **MSK-ACCESS**                      | [Link to AirTable](https://airtable.com/shr41mQwoEW82IWKq/tbl66CsfQyUIklV8r/viwSQRcKMCahyoxx9?blocks=biplLLHN2bdV0yeju)                                    |
| **CMO-CH**                          | [Link to AirTable](https://airtable.com/invite/l?inviteId=invetrtCfpSJxDTKO\&inviteToken=45e58de74abff25bebfeff5954190c152ed4236ecf388d080daf1f298a35f1df) |
| **CMO Cell-Free Informatics (CCI)** | [https://clickup.com/](https://clickup.com) - Request access once you have your msk email id                                                               |

## Functional Resources

| Assay/Purpose/Team/Tool                | URL                                                                                                                    |
| -------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **MSK-ACCESS V1 (Marianas)**           | [https://github.com/mskcc/ACCESS-Pipeline](https://github.com/mskcc/ACCESS-Pipeline)                                   |
| **CCI organization on Github**         | [https://github.com/msk-access](https://github.com/msk-access)                                                         |
| **cBioPortal DMP data**                | InternalLink: [https://github.mskcc.org/knowledgesystems/dmp-2022](https://github.mskcc.org/knowledgesystems/dmp-2022) |
| **Quality Control for ACCESS V1**      | [Access Quality Control (v1)](https://app.gitbook.com/o/-LhMNgvjydB3TFWAUMVb/s/-M52gq1rRSDQOKMQGEuR/ "mention")        |
| **Downstream analysis of ACCESS Data** | [https://cmo-ci.gitbook.io/access-data-analysis-v1/](https://cmo-ci.gitbook.io/access-data-analysis-v1/)               |
| **Fingerpriting using Biometrics**     | [https://cmo-ci.gitbook.io/biometrics/](https://cmo-ci.gitbook.io/biometrics/)                                         |
| **High Performance Computing**         | [https://mskcchpc.org/](https://mskcchpc.org)                                                                          |
| **Nucleo (Fgbio)**                     | [https://github.com/msk-access/nucleo](https://github.com/msk-access/nucleo)                                           |
| **Quality Control for ACCESS V2**      | [https://cmo-ci.gitbook.io/access-quality-control-v2/](https://cmo-ci.gitbook.io/access-quality-control-v2/)           |

## Path's to know

### CMO-ACCESS

#### Data on JUNO for CMO-ACCESS samples

| Analysis Type                       | JUNO Location                                                                                                |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **BAM**                             | **`/juno/work/access/production/data/bams/{cmo_patient_id}/{cmo_sample_id}/current/`**                       |
| **Small Variant (SNV’s/INDEL’s)**   | **`/juno/work/access/production/data/small_variants/{cmo_patient_id}/{cmo_sample_id}/current/`**             |
| **Microsatellite Instability(MSI)** | **`/juno/work/access/production/data/microsatellite_instability/{cmo_patient_id}/{cmo_sample_id}/current/`** |
| **Structural Variant (SV)**         | **`/juno/work/access/production/data/structural_variants/{cmo_patient_id}/{cmo_sample_id}/current/`**        |
| **Copy Number Variants (CNV)**      | **`/juno/work/access/production/data/copy_number_variants/{cmo_patient_id}/{cmo_sample_id}/current/`**       |

#### **Resources**

| Resource Type                                      | JUNO Location                                             |
| -------------------------------------------------- | --------------------------------------------------------- |
| **NYS validation data**                            | **`/work/access/production/runs/NYS_validation/current`** |
| **CMO-ACCESS**                                     | **`/work/access/production/`**                            |
| ****[**CMO-ACCESS Resources**](./#resources-1)**** | **`/work/access/production/resources/`**                  |
| **CMO-CH**                                         | **`/work/ch/`**                                           |
| **Berger Lab**                                     | **`/work/bergerm1/bergerlab`**                            |

#### Details of CMO ACCESS Resources

* `admie` - Files used for microsatellite instability detection tool ADMIE for MSK-ACCESS
* `cosmic` - VCF file of cosmic used in MSK-ACCESS workflows
* `dbSNP` - VCF file of dbSNP used in MSK-ACCESS workflows
* `exac` - VCF file of ExAC used in MSK-ACCESS workflows
* `mills-and-1000g` - VCF file of mills-and-1000g used in MSK-ACCESS
* `reference` - reference genome file used in MSK-ACCESS workflows
* `tools` - general packages used in MSK-ACCESS workflows
* `msk-access` - Data-specific resources for MSK-ACCESS workflows. This includes the following:
  * `hiseq4000_curated_duplex_bams_dmp` - curated DMP duplex BAMS from HiSeq 4000
  * `novaseq_curated_simplex_bams_dmp` - curated DMP simplex BAM from NovaSeq.
  * `hiseq4000_curated_simplex_bams_dmp` - curated DMP simplex BAM from HiSeq 4000
  * `novaseq_curated_standard_bams_dmp` - curated DMP standard BAM from NovaSeq
  * `hiseq4000_curated_standard_bams_dmp` - curated DMP standard BAM from HiSeq 4000
  * `novaseq_curated_unfiltered_bams_dmp` - curated DMP unfiltered BAM from NovaSeq
  * `hiseq4000_curated_unfiltered_bams_dmp` - curated DMP unfiltered BAM from HiSeq 4000
  * `novaseq_unmatched_normal_plasma_duplex_bams_dmp` - DMP unmatched normal plasma duplex BAM from NovaSeq
  * `hiseq4000_unmatched_normal_plasma_duplex_bams_dmp` - DMP unmatched normal plasma duplex BAM from HiSeq 4000
  * `novaseq_unmatched_normal_plasma_standard_bams_dmp` - DMP unmatched normal plasma standard BAM from NovaSeq
  * `hiseq4000_unmatched_normal_plasma_standard_bams_dmp` - DMP unmatched normal plasma standard BAM from HiSeq 4000
  * `novaseq_curated_duplex_bams_dmp` - curated DMP duplex BAMS from NovaSeq
  * `regions_of_interest` - Different interval files describing regions of interest for MSK-ACCESS assay

{% hint style="info" %}
<mark style="color:blue;">**If we can justify adding data/tools to the above-mentioned location please contact**</mark> [<mark style="color:blue;">**Ronak Shah**</mark>](mailto:shahr2@mskcc.org)<mark style="color:blue;">**.**</mark>
{% endhint %}
