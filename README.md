<p align="center">
  <img width="300" src="utils/SignatureSets_Logo.jpg">
</p>


# SignatureSets: An R Package for RNA-Based Immuno-Oncology Signatures

## Introduction
    
The `SignatureSets` package provides access to a curated and extensive compendium of RNA-based Immuno-Oncology (IO) signatures. All signatures included in this package are:

- Published in peer-reviewed literature.
- Publicly available through trusted repositories and resources.

References to the original publications and resources for each signature are included in the package documentation or accessible via the web application [predictio.ca](https://predictio.ca/). 

### Signature Association Types

In total, 55 IO gene signatures have been curated in the SignatureSets package. Notably, GENCODE version 40 was used to curate the signature data. These signatures are categorized based on their association with IO therapy outcomes:

- 65% (36 signatures): Associated with sensitivity to IO therapy, indicating potential positive responses such as immune activation or enhanced checkpoint inhibitor efficacy.

- 35% (19 signatures): Associated with resistance to IO therapy, highlighting mechanisms like immune evasion, suppressive tumor microenvironments, or other resistance pathways.

``` r

knitr::include_graphics("C:/SignatureSets/utils/SignatureSets_association.jpg")
                                                                                                                                                  ```
                           
## Methods for Computing IO Signature Scores

Signature scores are computed using standardized methods tailored to the signature’s characteristics as described in their original publication. 


## Citation 
                                                                  
If If the data from the SignatureSets package are used in your publication, please cite the following paper(s):                                                                  
- [Bareche, Y., Kelly, D., Abbas-Aghababazadeh, F. et al., Annals of Oncology 2022](https://pubmed.ncbi.nlm.nih.gov/36055464/).
                                                                                                                            
## Setup
                                                                 
The latest version of SignatureSets repository can be found on the [SignatureSets GitHub repository](https://github.com/bhklab/SignatureSets). To set up the repository, please download this folder locally:

``` bash

git clone https://github.com/bhklab/SignatureSets
cd SignatureSets

```

