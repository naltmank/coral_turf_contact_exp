# Introduction
Contains data and code for Altman-Kurosaki et al. 2024 (https://doi.org/10.1007/s00338-024-02585-7![image](https://github.com/user-attachments/assets/9422d464-1bd5-49d9-965c-e222c47f7578)
).

The data folder contains all data necessary to run the analyses in the code file (coral_turf_contact_exp_code.rmd). 

# Description of data
The data can be broadly broken up into three categories: turf species identification, photosynthetic yield data, and microbial data.

## Turf species identification data
turf_species_cover.csv provides information on turf cover used to produce Figure 1, with cover estimated from turf slides following Diaz-Pulido and McCook 2002. 

turf_species_list_wide.csv is used to create table S1.

## Photosynthetic yield data
Represents the PAM data collected over the course of the experiment. More specifically:

coral_algal_contact_data.csv is needed to produced results for the coral algal contact experiment (Figure 2),

turf_extract_pam_data_march.csv is needed to produced the results for the turf surface extract (Figure 3),

and turf_extract_pam_data_winter.csv is needed to produce the seasonal turf experiment (Figure 4).

## Microbial data
All remaining files represent data required to run the microbial analyses. Note that the qza files are QIIME outputs. Please contact Zoe Pratte and Frank Stewart for further details on the QIIME workflow necessary to produce these outputs. 
