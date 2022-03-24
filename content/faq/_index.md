+++
chapter = true
title = "FAQ"
weight = 50
+++

# COMMON QUESTIONS


While there are many questions you may have about the nature of the citation for your own project, we have tried to capture some of the common questions about software citation.


{{% expand "My software is released regularly as multiple versions, what should I do?" %}}


There are several options to consider in this situation:

**OPTION 1: Create one DOI that is used for all versions**

**Pros:** This is the simplest approach, and requires the least 
maintenance effort by the software creators.  

**Cons:** This approach can make it difficult to track citations to 
different software versions. There is likely to be less granularity in 
any citation metrics that accrue to the software. 

**Recommended practices:** Have the DOI resolve to a page that clearly displays all of 
the available software versions. Provide a clear citation example for 
each version that includes the version number in the recommended citation.

**OPTION 2: Create a new DOIs for each release version**

**Pros:** Enables users to precisely identify and point to specific versions 
of the software that they have used. 

**Cons:** Requires users to know how to 
reference the specific version that they used. Also requires the 
software creator/manager to take steps to create DOIs for each version. 
It also requires clear definitions of what a “version” means for the 
particular software project. 

**Recommended practices:** Create documentation that clearly defines 
what versions have been created, and their differences.  Have the DOIs 
resolve to a page that clearly displays the relevant software versions. 
Provide a clear citation example for each version that includes the 
version number in the recommended citation.  For software released 
through Github, strongly consider using Zenodo to create DOIs, as it 
creates DOIs for official Github releases when the Github-to-Zenodo 
plug-in has been activated.

**Considerations for assessing your version / release strategy**

* How much do you change your software?
* What is versionable about your software?
* How frequent do you make releases?
* How much traceability do you want? E.g. do you want to know which versions are being used most?
* Do multiple versions coexist in the user community?

{{% /expand %}}

{{% expand "A lot of the items in my repository are Jupyter Notebooks, should I mint a DOI for each notebook?" %}}

It is becoming commonplace for project software to be developed in the form of Jupyter Notebooks, and in some cases demonstration code is also in Jupyter.  The recommendation for Jupyter is to consider the logical cohesion of the "software" within the notebook (or notebooks).  If a notebook can be considered a **standalone artifact** and does not have dependencies with other notebooks or code not part of the software within the notebook, then it would be advised that a DOI is minted for that notebook.  If, however, a notebook is part of a larger set of notebooks or other software, it is advised you mint a DOI for the _collection_ of items and not just the notebook alone, especially if the collection is what you would like cited.  

One easy way to think of it is if the DOI was given out to the notebook (or collection), would it represent a useful whole as distributed.

{{% /expand %}}


{{% expand "What are the benefits of DOIs versus just a website URL?" %}}

A DOI is a persistent trackable identifier.  DOIs for software are increasingly being used in citation metrics which provide more visibility and greater understanding of how the identifier (and associated software) are linked to academic publications and other software.  Many academic indexing services are recognizing software DOIs as important trackable assets for metrics.

{{% /expand %}}


