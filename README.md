# eds-capstone
this is my capstone repo for the yale Environmental Data Science certification.
## Data Centre suitability: Singapore vs Malaysia
## Yale Environmental Data Science Certificate 2025-26: Capstone Project

# Overview
This project compares Singapore and Malaysia on data centre suitability using a composite score across four indicators: climate risk, grid stability, disaster resilience, and renewable energy share. Analysis is conducted in R using publicly available data.

# Repo structure
├── raw-data/        # Source datasets (see notebook for full descriptions and sources)
└── capstone-notebook.ipynb   # Main analysis notebook — all cleaning, analysis, and results

## Data sources
| Dataset | Source |
|---|---|
| Singapore temperature & rainfall | NEA via data.gov.sg |
| Malaysia temperature & precipitation | World Bank Climate Change Knowledge Portal |
| Singapore electricity generation & consumption | EMA via data.gov.sg |
| Malaysia electricity supply & consumption | DOSM via open.dosm.gov.my |
| Disaster resilience (INFORM Risk Index) | EU Joint Research Centre |
| Renewable energy share | Our World in Data / Ember |

## Notes
owid-energy-data.csv is large (~50MB) and not tracked in this repository. 
Download from: https://github.com/owid/energy-data
