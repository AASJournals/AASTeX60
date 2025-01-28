[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.593626.svg)](https://doi.org/10.5281/zenodo.593626)

# Version 6.3.2 is a LAST v6+ release of AASTeX
 It incorporates style and bug fixes provided by Alfred de Wijn (@dwijn) who posted v6.3.1 with style and bug fixes as a PR (#156).
 No further pull requests, bug fixes, or other code changes will be made to v6+. 

## AASTeX6
 The Version 6.3.2 style files and documentation for authoring [AAS Journal](https://journals.aas.org) articles in LaTeX2e  were developed on GitHub by the AASTeX user community as extensions of the official Version 6.3.1 release. 
 The official Version 6.3.1 release is available on [GitHub](https://github.com/AASJournals/AASTeX60/releases/tag/v6.3.1) and on the [AAS Journals website](https://journals.aas.org/aastex-package-for-manuscript-preparation/). 


## BibTeX
 This repository also includes the AAS Journals BibTeX style file, [aasjournal.bst](bst/aasjournal.bst), which was last updated June 3, 2019 (v1.18). This is our BST file that supports the `version` and `publisher` fields of an `@misc` BibTeX entry. 
 The most recent update added anchored links to reference source material, e.g., links to article DOIs, arXiv preprints, and/or [ASCL](http://ascl.net) identifiers. These are explicit inline text links to ensure that the identifiers are available in the full text. This is why we do not endorse more compact anchor-linked BibTeX styles, e.g., `yahapj.bst.`

## Download
 You may download the most recent version from this repository or from the [AAS Journals website](https://journals.aas.org/aastex-package-for-manuscript-preparation/). 

## Documentation
 In addition to the [sample files](sample) provided here, an extensive AASTeX guide can be found at our [AAS Journals website](https://journals.aas.org/aastex-package-for-manuscript-preparation/). Broader style, data, and graphics guides are also [available](https://journals.aas.org/author-resources/). 

## Development model
 AASTeX development is performed outside of the GitHub platform by a non-AAS TeX consultant. 
 Incremental updates from our developers are posted here, and we gladly accept user issues and bug reports. 
 **No further pull requests will be accepted to the v6 codebase.**

## Citation
 While the AAS Journals encourage developers to post preferred citations for their codes and encourage authors to cite all software that supports their research articles, citation of AASTeX or acknowledgement of the developers and maintainers of this package is traditionally considered inappropriate and is not requested.

## Contact
 Outside of issues about bugs, conflicts, or other AASTeX-related discussions, please contact the Journals team for help at our [AASTeX helpdesk](mailto:aastex@aas.org).

## Release History

| Version  | Github Release   | DOI  |
| -------- |:----------------:| -----|
| [v6.0.1](https://github.com/AASJournals/AASTeX60/tree/v6.0.1)   | 2016 January 26  | [10.5281/zenodo.45282](https://doi.org/10.5281/zenodo.45282) |
| [v6.0.2](https://github.com/AASJournals/AASTeX60/tree/v6.0.2)   | 2016 March 02    | tbd |
| [v6.1](https://github.com/AASJournals/AASTeX60/tree/v6.1)       | 2016 November 23 | [10.5281/zenodo.168228](https://doi.org/10.5281/zenodo.168228) |
| [v6.2](https://github.com/AASJournals/AASTeX60/tree/v6.2)       | 2018 February 23 | [10.5281/zenodo.1209290](https://doi.org/10.5281/zenodo.1209290) |
| [v6.3](https://github.com/AASJournals/AASTeX60/tree/v6.3)       | 2019 August 8 | [10.5281/zenodo.3675798](https://doi.org/10.5281/zenodo.3675798) |
| [v6.3.1](https://github.com/AASJournals/AASTeX60/tree/v6.3.1)   | 2025 January 27 | [10.5281/zenodo.14757029](https://doi.org/10.5281/zenodo.14757029) |
| [v6.3.2](https://github.com/AASJournals/AASTeX60/tree/v6.3.2)   | 2025 January 28 | [10.5281/zenodo.14757296](https://doi.org/10.5281/zenodo.14757296) |

## Credit
AASTeX originated 28 years ago with a set of LaTeX macros developed by [Bob Hanisch and Chris Biemesderfer](https://ui.adsabs.harvard.edu/#abs/1989BAAS...21..780H/abstract). While a more detailed history is available in the [sample document](sample/sample61.tex), we want to recognize the most recent contributions of individual astronomers to AASTeX 6 here. A partial list includes:

+ Dan Foreman-Mackey (@dfm) and David Hogg (@davidwhogg) authored a [series of readability and layout modifications of AASTeX v6.0](https://github.com/dfm/peerless/blob/master/document/ms.tex#L19-L69) in a recent manuscript that were incorporated into v6.1 as the *"modern"* document style.
+ We thank the many users who have supplied issues directly to the AAS Data Editors in charge of AASTeX development or as issues (ongoing or closed) on this repository. 
+ For Version 6.3.2, we especially thank Alfred de Wijn (@dwijn) who posted v6.3.1 with style and bug fixes as a PR (#156) that we took much too long to accept. This PR forms the core of the final v6.3.2 release. 
