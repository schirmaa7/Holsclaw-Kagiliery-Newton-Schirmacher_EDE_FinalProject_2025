# Holsclaw-Kagiliery-Newton-Schirmacher_EDE_FinalProject_2025
EDE Final Project Spring 2025


## Summary

The purpose of this repository is to analyze the value of commercial fishing landings 
in North Carolina. It contains data from the North Carolina Department of Environmental
Quality (NCDEQ) on landings catch, value, species, and landings value by county for
the years 2014 - 2022. It contains code for the analysis, the raw data, and the 
final results of this analysis. The goal of this work is to examine patterns in 
commercial fishing by species over time - this kind of information is important for
fisheries management and understanding local demands of the seafood industry. 

## Investigators

- Natalie Holsclaw, MEM Candidate, natalie.holsclaw@duke.edu
- Julia Kagiliery, MEM Candidate, julia.kagiliery@duke.edu
- Tori Newton, MEM Candidate, tori.newton@duke.edu
- Ayden Schirmacher, MEM Candidate, ayden.schirmacher@duke.edu


## Keywords

Fisheries management, commercial landings, North Carolina


## Database Information

All raw data were obtained from the North Carolina Department of Environmental
Quality (NCDEQ) Fisheries Statistics and was downloaded in March 2025. North 
Carolina County shape files were obtained from the ENVIRON 872L repository. Data
were wrangled, cleaned, and processed in the repository script files. 


## Folder structure, file formats, and naming conventions 

Folders in the repository:

1. Code: Contains R markdown files with all code used in the data exploration 
and analysis.

2. Data: Contains a 'Raw' folder with raw data files downloaded from the NCDEQ,
the 'Processed' folder contains data relevant to our spatial analysis. 

3. Output: Contains the final .html of the project analyses. 

### File formatting:

Raw data are contained in .csv files, code is kept in R markdown files,
the final report is also in a R markdown format and knitted to an .html file, 
and county data is in a shapefile format. 


### Naming Conventions

Raw data are named with the year they represent. The final script is named
'GroupDocument_FinalProject' previous versions of scripts are named with
the owners name and '_FinalProject'. The final report contains author last
names and '_ENV872_Project'. 


## Metadata

Raw data files (named by year, same information for all years):
- Columns:
  - 'Fish' - species common name (chr)
  - 'Final Weight' - Weight of landings in pounds (lbs) - (int)
  - 'Final Value' - Value in US Dollars of landings (int)

Raw county data file: 'stats_fishies.csv'
- Columns:
  - 'County' - North Carolina county (chr)
  - 'Year' - Year the data represents (Date)
  - 'Pounds' - Weight of landings in pounds (lbs) - (int)
  - 'Value' - Value in US Dollars of landings - (int)

## Scripts and code

- 'SchirmacherAyden_FinalProject.Rmd' - inital exploration and analysis of data
- 'SchirmacherAyden_Counties_FinalProject.Rmd' - mapping of county data
- 'GroupDocument_FinalProject.Rmd' - combined script of analyses by all investigators
- 'Holsclaw_Kagiliery_Newton_Schirmacher_ENV872_Project.Rmd' - markdown file of
final analyses and interpretations included in final report. 



