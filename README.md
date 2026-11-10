# EDS223-HW2
Homework 2: Exploring patterns of enviromental justice 
---
* **Author:** Amapola Garcia
* **Date:** October 24,2026
* **Course Name:** Geospatial Analysis and Remote Sensing
* **Term:** Fall 2026

## About:
---
Present-day environmental justice may reflect legacies of injustice in the past. The United States has a long history of racial segregation which is still visible. During the 1930’s the Home Owners’ Loan Corporation (HOLC), as part of the New Deal, rated neighborhoods based on their perceived safety for real estate investment. Their ranking system, (A (green), B (blue), C (yellow), D (red)) was then used to block access to loans for home ownership. 

## Purpose:
With R code we will be working with three different datasets:
1. EJScreen : Provides enviromental and demographic information about US Census levels
2. HOLC Redlining: Provides the digitized map and information about HOLC
3. Bike and Pedestrian Crash Reports: Statewide Integrades Traffic Records System database that collects and processes data gathered from collision scense.

To provide insights of redlining in current enviormental injustice within Los Angeles County,CA.

## Instructions & Installation:
---
Downloading and installing steps:
1. Download Libraries and read datasets
2. Transform HOLC into CRS
### Part I.
* Create a visual map of historical redlining colored neighborhoods by HOLC Grade
* Create a Table summarizing Census blocks groups that fall within each HOLC Grade in Los Angeles,CA
*  Create two visualization of current conditions within HOLC Grade
    * Average % expectancy visualization
    * Average % of Low-income by HOLC Grade
### Part II.
* Create a visual map and table of Redlining in pedestrian and bike accidents

### Part III.
* Summarize your findings.

### Instructions
EDS223-HW2
│   README.md
│   HW2.qmd
│   Rmd/Proj files    
│
└───.gitignore
     └───data
         └───ejscreen
         └───SWITRS_LA
         └───mapping-inequality


## Datasets
* ejscreen","EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
* mapping-inequality/mapping-inequality-los-angeles.json
* crashes.csv


## References and Acknowledgement
Gee, G. C. (2008). A multilevel analysis of the relationship between institutional and individual racial discrimination and health status. American journal of public health, 98(Supplement_1), S48-S56.↩︎

Nardone, A., Rudolph, K. E., Morello-Frosch, R., & Casey, J. A. (2021). Redlines and greenspace: the relationship between historical redlining and 2010 greenspace across the United States. Environmental health perspectives, 129(1), 017006.↩︎

Hoffman, J. S., Shandas, V., & Pendleton, N. (2020). The effects of historical housing policies on resident exposure to intra-urban heat: a study of 108 US urban areas. Climate, 8(1), 12.↩︎

Taylor, N. L., Porter, J. M., Bryan, S., Harmon, K. J., & Sandt, L. S. (2023). Structural racism and pedestrian safety: Measuring the association between historical redlining and contemporary pedestrian fatalities across the United States, 2010–2019. American Journal of Public Health, 113(4).↩︎

Robert K. Nelson, LaDale Winling, Richard Marciano, Nathan Connolly, et al., “Mapping Inequality,” American Panorama, ed. Robert K. Nelson and Edward L. Ayers, accessed October 17, 2023, https://dsl.richmond.edu/panorama/redlining/↩︎
