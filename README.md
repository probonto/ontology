# ProbOnto: ontology and knowledge base of probability distributions

[ProbOnto](http://probonto.org) is an ontology and knowledge base of probability distributions. 

This repository hosts versioned technical releases, development snapshots of ProbOnto and supporting material. 

## Releases

Technical releases follow their own process and do not necessarily occur together with human readable documentation releases. The OWL implementation only partially covers the content of the documented ProbOnto knowledge base. 

Releases intended for use are found in the _release_ directory. For details regarding each release, consult the relevant release notes. 

## Documentation 

For the main documentation regarding ProbOnto and its content, consult [ProbOnto's website](http://probonto.org) and the PDF documents available for download. Additional documentation material can be gathered from the _doc_ directory of this repository. 

The coverage provided in the OWL implementation of ProbOnto for versions 2.x can be illustrated with the type of information encoded for [Normal1](doc/Normal1Doc-v2.0.txt). The file is an excerpt from the OWL encoding of ProbOnto v2.0 containing RDF statements whose subject is Normal1 and examples of each of the entities related to Normal1, yet it is not listing all entities so-related within the OWL file (Normal1 has more associated functions, moments and parameter defined in the same ways as those illustrated). 

## Usage 

### OWL files usage

Download the latest release. OWL files can be used in a variety or tools and libraries. See [licence](LICENCE.md).

### OLS provision 

probonto4ols.owl is an endpoint for the EBI's OLS allowing OLS-style [access](http://www.ebi.ac.uk/ols/ontologies/probonto). This file is updated with minor revisions of the OWL implementation of ProbOnto. 
