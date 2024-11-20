# README for Variant Calling Pipeline for SARS-CoV-2 using Illumina short reads

Parts of this pipeline approach are based on the pipeline described in the [Data Carpentry Genomics lessons](https://datacarpentry.org/genomics-workshop/), which are made available under a [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).

Daniela Dueñas    
dduenas4@dons.usfca.edu    
November 19, 2024    

## Project Overview

For this project, I will be analyzing the sequences data from SRA BioProject PRJNA745219, which aimed to understand how SARS-CoV-2 affects different cell tissues and among different species. The goal for this analysis will be to recall and utilize bioinformatic methods learned throughout the BIOL-422 course to develop figures and tables that will present the main findings of the sequence data. The analysis will help dqevelop a Report based on the following data from the BioProject: _run number_, _number of bases_, _organism_, _cell line_, _tissue type_, and _treatment given (SARS-CoV-2 or mock infection)_.

## Project Outline

+ The project will utilize GitHub, RStudio, and BASH/Linux system.
+ On RStudio, the following packages will need to be installed and/or updated: `ggplot2`, `dplyr`, `knitr`, `lintr`, and `citr`.
+ The sequence data spreadsheet must be copied and the copy will be edited to follow **Tidyverse** guidelines prior to running the code.
+ Due to the inclusion of human and non-human model organism samples, function code in an R script will code for separate data frames for each organism.
+ Function code R script will be sourced into an RMarkdown file and run on the sequence data to develop the different data frames.
+ `ggplot2` will be used to develop figures and tables from the analyzed data frames.
+ Given the size of the sequence data, a complete analysis will be done on the Linux system and use a **BASH** script to parse the data.
+ Running the data on the **BASH** script will be completed on _tmux_ and results will automatically be placed into a _txt_ file.
+ All scripts, the markdown file, and output files will be continually pushed and commited to the personal "bioinformatics-final-project" GitHub repository, forked from the class repository.
