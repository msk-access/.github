---
cover: >-
  https://images.unsplash.com/photo-1461749280684-dccba630e2f6?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHw5fHxTb2Z0d2FyZXxlbnwwfHx8fDE2NDQyNjM0MDc&ixlib=rb-1.2.1&q=85
coverY: 0
---

# Software Engineers

{% hint style="warning" %}
<mark style="color:blue;">**Please visit this page once you have done things necessary here:**</mark> [**https://mskcc.github.io/on-boarding/**](https://mskcc.github.io/on-boarding/)****
{% endhint %}

* The best place to start would be to understand the data flow:&#x20;
  * <mark style="color:green;">**LIMS/SMILE -> Voyager -> JUNO**</mark>
* Learn more about the codebases listed below that form Voyager
* Learn about the codebases the form mPATH

## Sites

### Code/Project Management

| Resource                                                                                                                         | URL                                                                                                                                                                                                             |
| -------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ACCESS/Voyager team uses this to manage sprints/stories. In addition, ACCESS uses this to keep track of the statuses of samples. | [clickup.com ](https://clickup.com)                                                                                                                                                                             |
| Auto Track Sample Status                                                                                                         | [jira.mskcc.org:8090](https://jira.mskcc.org:8090)                                                                                                                                                              |
| Internal Gitlab where MPath and other software is hosted.                                                                        | <p><a href="http://crux.mskcc.org:8929/mpath">http://crux.mskcc.org:8929/mpath</a></p><p><a href="http://crux.mskcc.org:8929/access">http://crux.mskcc.org:8929/access</a> (forked from mpath repositories)</p> |
| Code specific to ACCESS team pipelines.                                                                                          | [github.com/mskcc-access](https://github.com/mskcc-access)                                                                                                                                                      |
| Code for other CMO/MSK teams                                                                                                     | [github.com/mskcc](https://github.com/mskcc)                                                                                                                                                                    |
| Information on HPC/LSF                                                                                                           | [https://mskcchpc.org/](https://mskcchpc.org/)                                                                                                                                                                  |
| Beagle                                                                                                                           | [https://github.com/mskcc/beagle](https://github.com/mskcc/beagle)                                                                                                                                              |
| Hermes                                                                                                                           | [https://github.com/mskcc/hermes](https://github.com/mskcc/hermes)                                                                                                                                              |
| Ridgeback                                                                                                                        | [https://github.com/mskcc/ridgeback](https://github.com/mskcc/ridgeback)                                                                                                                                        |

### Applications

| Application                                                  | URL                                                                                                                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| LIMS                                                         | For Authentication ask your Manager: [https://igolims.mskcc.org:8443/LimsRest/swagger-ui.html](https://igolims.mskcc.org:8443/LimsRest/swagger-ui.html) |
| Beagle API                                                   | <ul><li>http://silo:4001 <strong>(Staging)</strong></li></ul><ul><li>http://voyager:5001 (<strong>Production)</strong></li></ul>                        |
| Ridgeback API                                                | <ul><li>http://silo:4003 <strong>(Staging)</strong></li></ul><ul><li>http://voyager:5003 (<strong>Production)</strong></li></ul>                        |
| Flower (Celery Task UI) for Voyager, **for Production only** | http://voyager:4001                                                                                                                                     |
| ELK for Voyager                                              | [bic-dockerapp01.mskcc.org:5601/](http://bic-dockerapp01.mskcc.org:5601/)                                                                               |
| MPath (for Clinical)                                         | [https://mpath.mskcc.org/](https://mpath.mskcc.org/)                                                                                                    |
| MPath (for Research)                                         | http://access01:7331/api/ui/                                                                                                                            |
| CVR (to be replaced by MPath)                                | cvr.mskcc.org:8083/                                                                                                                                     |

## People

Projects, who to speak with, slack channel

* MPath & CVR ([Aijazuddin Syed/Anoop Balakrishnan Rema](collaborations.md#clinical-bioinformatics-clinbx))
* Voyager Projects \[Beagle/Seqosystem/Ridgeback] ([Sinisa Ivkovic/Nikhil Kumar/Allan Bolipata](collaborations.md#cmo-informatics-ci))
  * \#voyager
* LIMS ([David Mcmanamon](collaborations.md#integrated-genomics-operations-igo))
* MDB (Angelica Ochoa/Benjamin Gross/Allan Bolipata)
  * \#metadb-informatics
* Toil/CWL (Nikhil Kumar)
* ACCESS (Ronak Shah)
  * \#msk-access
* ACCESS Servers ([HPC Request/Neeraj Paramasivam](collaborations.md#high-performance-computing-hpc))
