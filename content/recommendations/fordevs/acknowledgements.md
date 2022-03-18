+++
chapter = true
title = "Attribution & Acknowledgement"
weight = 12
+++


## Software Attribution & Acknowledgement

Providing clear acknowledgement instructions to your end users required appropriate languae and file placement where end users are most likely to see it, such as your software landing page or Github `README` file.


### Your software package’s web page or Github repository should include language indicating how you would like attribution:

* The information you place on your site should provide clear instructions on how you would like your citation to appear. Provide a clear example of the citation as you would like it to appear in publications and other works that cite your software.
* If your software is hosted on a web page, that page should provide a recommended citation. 
* If your software is hosted on Github, the  `README.MD` file should provide a recommended citation, so if users find the landing page but have not yet visited the source code, they can quickly understand how to cite the work. Here is an example from the [wrf-python](https://github.com/ncar/wrf-python) software package repository on github:


![](/recommendations/fordevs/wrfpy-github-01.png)


### Add a Software DOI Badge to your Github Repository

DOI badges help improve the visibility of your software on your software repository. This is a very simple way to let your visitors and end users know that a DOI exists and that they are being encouraged to use it.

You can add a DOI badge very easily to your top-level master branch README.md file with the following shortcode that uses the [shields.io](https://shields.io) badge catalog:

```
[![DOI](https://img.shields.io/badge/DOI-YOUR_ DOI)](https://doi.org/YOUR_DOI)
```

And once you add this to the first line of your README.md, your badge will look like this:

![](/recommendations/fordevs/doi-badge-01.png)


### Include CITATION File Format (CFF) file in the root of your repo.

This is a relatively new addition to Github that allows you to add structured citation information directly into your Github repository.  See the [Github Guide for CITATION Files](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files) for additional information, as well as detailed information about the [Citation File Format (CFF)](https://citation-file-format.github.io/).


### † (Advanced) Include a command in the software that allows users to generate a citation:

You can optionally include a command in the software that allows users to generate a citation. The [latticekrig project](https://cran.r-project.org/web/packages/LatticeKrig/index.html) makes heavy use of the R programming language. To encourage citation and to remind users that within their R environment that they may get an example of the citation as the authors intended, the `citation("latticekrig")` command in the language will generate the citation with the current running version of the software.