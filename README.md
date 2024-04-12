[![DOI](https://zenodo.org/xxxxxxx.svg)](https://doi.org/xxxxx)

This repository contains data and code to accompany the manuscript titled

### Measuring multi-year changes in the Symbiodiniaceae algae in Caribbean corals on coral-depleted reefs

by Ross Cunning, Elizabeth A. Lenz, and Peter J. Edmunds

In this manuscript, we present a three-year time series tracking the algal symbionts in tagged colonies of nine coral species in St. John, U.S. Virgin Islands, spanning major biotic and abiotic disturbances. 

#### Repository contents:
    
* **Data/:**
    + STJ_Metadata_2017_2019.csv: Metadata for all coral samples for this study, including colony ID, taxonomy, collection date, depth, and location.
    + 20200623_lenz: Directory containing ITS2 metabarcoding data output from SymPortal analysis.
    + **Note: raw sequence data for this project can be found at: https://doi.org/10.5061/dryad.02v6wwq95
    
* **Analysis/:** 
    + ITS2_analysis.Rmd: This RMarkdown document contains code to import and analyze ITS2 metabarcoding data. Statistical analysis and visualization is performed on count tables of ITS2 sequence variants and ITS2 type profiles that have been processed through SymPortal.
    
* **Output/:** contains figures and tables used in the associated manuscript and supplementary information file. Figures are created and written to file in Analysis/ITS2_analysis.Rmd.