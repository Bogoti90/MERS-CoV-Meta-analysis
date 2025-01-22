# MERS-CoV Meta-analysis
 MERS-CoV systematic review and Meta-analysis in Africa

## Overview
This repository contains R code for analyzing MERS-CoV prevalence data in Africa, focusing on both dromedary camels and human cases. The analysis includes spatial distribution, temporal trends, and meta-analysis of the prevalence data.

## Prerequisites
Required R packages:
- tidyverse
- openxlsx
- spData
- maps
- maptools
- rworldmap
- sf
- ggsn
- janitor
- esc
- meta
- metafor

## Data Requirements
The analysis requires the following input files:
- FAOSAT_camel_data.xlsx
- MERS-Review Extraction tool_2024.xlsx

## Directory Structure
```
.
├── data/
│   ├── FAOSAT_camel_data.xlsx
│   └── MERS-Review Extraction tool_2024.xlsx
├── figures/
├── R/
│   └── analysis.Rmd
└── README.md
```

## Analysis Components
1. Spatial distribution of MERS-CoV studies in Africa
2. Temporal analysis of research publications
3. Seroprevalence analysis for both dromedaries and humans
4. Meta-analysis and forest plots
5. Meta-regression analysis

## Usage
1. Clone this repository
2. Place your data files in the `data/` directory
3. Open the R project and run the analysis.Rmd file
4. Output figures will be saved in the `figures/` directory

## Output Files
The analysis generates several visualization outputs:
- Distribution maps of studies
- Temporal trends of publications
- Forest plots for meta-analysis
- Funnel plots
- Odds ratio visualizations

## Citations and Data Sources
[Add relevant citations and data sources]

## License
[Add your chosen license]

## Contact
[Add your contact information]
