+++
chapter = true
title = "Persistent Identifiers"
weight = 11
+++

## Persistent Identifiers


Three potential ways to get a persistent identifier are as follows:


### Github-to-Zenodo export

If you have your software in a Github repository, Zenodo provides a DOI minting 
service directly from Github. Zenodo extracts and archives a snapshot of your Github 
repository as it was at a specific time, and assigns a DOI to that snapshot. Make 
sure that you check the author list after exporting to Zenodo, in particular to 
change Github monikers to authors’ names and add ORCIDs when missing. Also, make sure 
the title of your Github repository is meaningful before you export to Zenodo. 

**Benefits** 

* If your software is released in discrete releases, and you want different DOIs to be 
assigned with each of your releases, the Zenodo integration with Github may be 
useful, as can be tightly integrated with the project releases within your 
repository. 
* Preservation is done by Zenodo, which is operated by the CERN high-energy 
physics facility in Europe.

**Drawbacks** 

* Zenodo integration only works with Github. 
* The snapshotted version in Zenodo can become out of sync with the most current software in Github. 
* No curation support.


### University library repository

Some university libraries offer the capability to archive software in their digital 
repositories. They typically also assign persistent identifiers to their repository’s 
resources, often DOIs. 

**Benefits**
 
* Local & in-person service from professional staff at your local organization. 
* Curation support for creating metadata, organizing files, and the archiving process. 

**Drawbacks** 

* Many university library digital repositories are designed to take in many different 
kinds of digital assets, such as data sets, documents, and images. Thus, their 
services may not be designed specifically for software, and may not have any features 
that directly support software.


Some, 
however, are developing services specifically to host software. 

### Software Heritage 
Software Heritage is an initiative aiming to collect, preserve, and share the entire 
body of software source code and its development history. 

**Benefits**

* The Software Heritage services are specifically designed for software preservation 
and tracking. 

* Fine grained tracking and reference of software - Software Heritage IDs can be used 
to reference specific versions of software source projects and source code files, 
down to fragments of individual files. Ex: this URL references lines 14-20 of a 
specific file within the Software Heritage archive: 
https://archive.softwareheritage.org/browse/content/sha1_git:2f1b8cc8aed317ad1ae83310fc3fabf4f339bca6/?origin_url=https://github.com/pangeo-data/pangeo&path=a618ecbf43e04f12b39bec8e5d0145ff1795ad69/.travis.yml&revision=8f1343558d7c0eecf4aa1001329b9bdfb3efe00f&snapshot=3b3af1c32cc2dfc8ec9b509a19acf570a07d3c58#L14-20

**Drawbacks**

* Software Heritage does not use DOIs to identify their software. 
* They have their own identifier system. 
* Publishers may expect/require DOIs. 
* SH IDs can be long and unwieldy, as shown in the above example 
* No curation support. 
* No metadata requirements.

