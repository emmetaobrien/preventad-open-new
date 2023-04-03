# PREVENT-AD open Dataset

### Overview

The PREVENT-AD (Pre-symptomatic Evaluation of Experimental or Novel Treatments for Alzheimer Disease) cohort is composed of cognitively healthy participants over 55 years old, at risk of developing Alzheimer Disease (AD) as their parents and/or siblings were/are affected by the disease. These ‘at-risk’ participants have been followed for a naturalistic study of the presymptomatic phase of AD since 2011 using multimodal measurements of various disease indicators. One clinical trial intended to test a pharmaco-preventive agent has also been conducted.

The PREVENT-AD research group is now releasing data openly with the intention to contribute to the community’s growing understanding of AD pathogenesis.

More detailed information about the study design can be found in the LORIS instance of Open PREVENT-AD (https://openpreventad.loris.ca).

### Data organization

For the BIDS dataset, please visit https://portal.conp.ca/dataset?id=projects/preventad-open-bids

Data are organized by `candidate_id/visit_label`:

```
preventad-open
|__DATS.json
|__candidate_id
   |__candidate.json
   |__visit_label
      |__visit.json
      |__handedness.json
      |__images
         |__image_1.mnc
         |__image_2.mnc
         |__image_3.mnc
```

- `DATS.json` is a JSON file that describes the content of the dataset
- `candidate.json` contains demographic information regarding the candidate in question
- `visit.json` contains visit level information
- `handedness.json` when present, contains results of the Handedness Edinburgh Inventory
- images are provided in MINC format

### For more information: 

- LORIS open database instance with the PREVENT-AD dataset: https://openpreventad.loris.ca
- Open PREVENT-AD BIDS dataset: https://portal.conp.ca/dataset?id=projects/preventad-open-bids
- PREVENT-AD study web site: https://prevent-alzheimer.net/
- PREVENT-AD Twitter account: https://twitter.com/prevent_ad
- Dataset DOI: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3991997.svg)](https://doi.org/10.5281/zenodo.3991997)

