# Global cold-water coral diversity dataset

## About this dataset

This dataset provides a comprehensive and quality-controlled distribution data for cold-water corals of the orders Alcyonacea, Antipatharia, Pennatulacea, Scleractinia, Zoantharia of the subphylum Anthozoa, and order Anthoathecata of the class Hydrozoa. Distribution records were gathered from online repositories and literature sources, standardized with the Darwin Core Standard, dereplicated, taxonomically corrected and flagged for potential geographic and vertical distribution errors based on peer-reviewed literature and expert consulting.

It was published in the journal __Data in brief__ (https://doi.org/10.1016/j.dib.2023.109223) and in FigShare (https://doi.org/10.6084/m9.figshare.21997559.v2), and was authored by Eliza Fragkopoulou, Viktoria Balogh, Ester Serrão, Jorge Assis.

The first version of the dataset is available since 22-02-2023 and is licensed under a CC BY 4.0 license.

## Workflow

[source data](https://github.com/iobis/mpaeu_di_globcw_coral/tree/master/data/raw) → Darwin Core [mapping script](https://github.com/iobis/mpaeu_di_globcw_coral/blob/master/src/obisdi_general.Rmd) → generated [Darwin Core files](https://github.com/iobis/mpaeu_di_globcw_coral/tree/master/data/processed)

## Additional metadata

In this repo we include all the data that is __not__ derived from OBIS in the OBIS database. We decided to include all records (not the prunned ones) with the respective flags (as a MeasurementOrFact), so users have the chance to analyze the data for themselves and select according to their judgment of the flags.

## Published dataset

* [Dataset on the IPT]({once published, link to the published dataset})
* [Dataset on OBIS]({once published, link to the published dataset})

## Repo structure

Files and directories indicated with `GENERATED` should not be edited manually.

```
├── README.md              : Description of this repository
├── LICENSE                : Repository license
├── mpaeu_di_globcw_coral.Rproj : RStudio project file
├── .gitignore             : Files and directories to be ignored by git
│
├── data
│   ├── raw                : Source data, input for mapping script
│   └── processed          : Darwin Core output of mapping script GENERATED
│
├── docs                   : Repository website GENERATED
│
└── src
    ├── dwc_mapping.Rmd    : Darwin Core mapping script
    ├── _site.yml          : Settings to build website in docs/
    └── index.Rmd          : Template for website homepage
```
<!-- Please don't edit below this line -->
<!-- PACKAGE DETAILS -->
<br>
<!--INSTITUTIONAL_DETAILS--> Dataset edited by the OBIS secretariat.  <br><br>
<!--FUNDING_DETAILS--> The harvesting of this data to OBIS is part of the MPA Europe project. <br><br> MPA Europe project has been approved under HORIZON-CL6-2021-BIODIV-01-12 — Improved science based maritime spatial planning and identification of marine protected areas. <br><br>
            Co-funded by the European Union. Views and opinions expressed are however those of the authors only and do not necessarily reflect those of the European Union or UK Research and Innovation.
            Neither the European Union nor the granting authority can be held responsible for them  <br><br>
This repository was created using the
`obisdi` package [(download here)](https://github.com/iobis/obisdi/) and was inspired by the [TrIAS
Project checklist
recipe](https://github.com/trias-project/checklist-recipe/). This
README is a direct adaptation of the TrIAS model, with slight changes.
<br>  
<img style="float: left; margin-right: 20px;" src="src/static/obisdi_logo.png" width="60">
<hr>

OBIS Data Ingestion \| Ocean Biodiversity Information System
[(obis.org)](https://obis.org/)
