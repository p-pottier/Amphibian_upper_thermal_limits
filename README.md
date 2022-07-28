# A comprehensive database of amphibian heat tolerance

Cite this dataset as **Patrice Pottier, Hsien-Yung Lin, Rachel R. Y. Oh, Pietro Pollo, A. Nayelli Rivera-Villanueva, José O. Valdebenito, Yefeng Yang, Tatsuya Amano, Samantha Burke, Szymon M. Drobniak, and Shinichi Nakagawa. (2022) A comprehensive database of amphibian heat tolerance** [![DOI](https://zenodo.org/badge/494322085.svg)](https://zenodo.org/badge/latestdoi/494322085)


This repository contains data records for a Data descriptor submitted to *Scientific Data*. 

Below is a description of the different folders and their content.

Please feel free to contact Patrice Pottier (p.pottier@unsw.edu.au) if you need assistance navigating these documents.

### data/

* `Raw_data.csv`: Raw data extracted from the studies. Note that this data has been checked for errors and can be re-used. However, this dataset contains numerous sources of variation, including data having potential procedural concerns (see below)

* `Curated_data.csv`: Curated version of the dataset. This dataset excludes which excludes data having procedural concerns; animals exposed to toxicants, hormones, or high levels of UV radiations; extinct species; and species not described at the species level. We recommend using this dataset to address most questions in ecophysiology. 

* `Metadata.csv`: Description of the different variables in the database.

* `amph_shl_new_Classification.csv`: Supplementary data by Pyron & Jetz (2018) https://doi.org/10.1038/s41559-018-0515-5 containing taxonomic information.

* `amph_shl_new_Consensus_7238.tre`: Consensus tree sampled from the posterior distribution by Pyron & Jetz (2018) https://doi.org/10.1038/s41559-018-0515-5 

### R/

* `Data_curation.Rmd`: Code detailing the different steps of the data curation 

* `Figures_data_descriptor`: Code for producing the figures in this data descriptor 

### references/

* `All_references.ris`: Bibliographic file containing all the references included in the database.
