[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1209290.svg)](https://doi.org/10.5281/zenodo.1209290)

## AASTeX6
The Version 6.2 style files and documentation for authoring [AAS Journal](http://journals.aas.org) articles in LaTeX2e were released on January 8, 2018. A list of updates and changes provided by Version 6.2 can be found in the [AASTeX Revision History](http://journals.aas.org/authors/aastex/revisionhistory.html). Version 6.2 is backwards compatible with v6.1 but no prior version of AASTeX.

## BibTeX
This repository also includes the AAS Journals BibTeX style file, [aasjournal.bst](bst/aasjournal.bst), which was last updated October 26, 2017. This is our BST file that supports the `version` and `publisher` fields of an `@misc` BibTeX entry. The most recent update added anchored links to reference source material, e.g., links to article DOIs, arXiv preprints, and/or [ASCL](http://ascl.net) identifiers.

## Download
You may download the most recent version from this repository or from the [AAS Journals website](http://journals.aas.org/authors/aastex.html). 

## Documentation
In addition to the [sample files](sample) provided here, an extensive AASTeX guide can be found at our [AAS Journals website](http://journals.aas.org/authors/aastex/aasguide.html). Broader style, data, and graphics guides are also [available](http://journals.aas.org/authors/). 

## Development model
AASTeX development is performed outside of the GitHub platform, but incremental updates from our developers are posted here regularly, and we gladly accept issues and user pull requests. 

## Citation
While the AAS Journals encourage developers to post preferred citations for their codes and encourage authors to cite all software that supports their research articles, citation of AASTeX or acknowledgement of the developers and maintainers of this package is traditionally seen as inappropriate and is not requested.

## Contact
Outside of issues or pull requests, please contact the AASTeX team for help at our [authoring helpdesk](mailto:authors@aas.org) or reach us on Twitter [@AAS_Publishing](https://twitter.com/AAS_Publishing).

## Release History

| Version  | Github Release   | DOI  |
| -------- |:----------------:| -----|
| [v6.0.1](https://github.com/AASJournals/AASTeX60/tree/v6.0.1)   | 2016 January 26  | [10.5281/zenodo.45282](https://doi.org/10.5281/zenodo.45282)|
| [v6.0.2](https://github.com/AASJournals/AASTeX60/tree/v6.0.2)   | 2016 March 02    | tbd       |
| [v6.1](https://github.com/AASJournals/AASTeX60/tree/v6.1)       | 2016 November 23 | [10.5281/zenodo.168228](https://doi.org/10.5281/zenodo.168228)       |
| [v6.2](https://github.com/AASJournals/AASTeX60/tree/v6.2)       | 2018 February 23 | [10.5281/zenodo.1209290](https://doi.org/10.5281/zenodo.1209290)       |


## Credit
AASTeX originated 28 years ago with a set of LaTeX macros developed by [Bob Hanisch and Chris Biemesderfer](https://ui.adsabs.harvard.edu/#abs/1989BAAS...21..780H/abstract). While a more detailed history is available in the [sample document](sample/sample61.tex), we want to recognize the most recent contributions of individual astronomers to AASTeX 6 here. A partial list includes:

+ Dan Foreman-Mackey (@dfm) and David Hogg (@davidwhogg) authored a [series of readability and layout modifications of AASTeX v6.0](https://github.com/dfm/peerless/blob/master/document/ms.tex#L19-L69) in a recent manuscript that were incorporated into v6.1 as the *"modern"* document style.
+ We thank the many users who have supplied issues directly to the AAS Data Editors in charge of AASTeX development or as issues (ongoing or closed) on this repository. We especially thank Alex Drlica-Wagner (@kadrlica) for developing fixes to many of the issues identified by authors. He also maintains a fork that is pretty much always ahead of ours, as we almost never accept his otherwise excellent PRs. 
