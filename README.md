# scDehashR
The purpose of this app is to develop an interactive Shiny portal that can dehash any number of pooled samples from single cell techniques for easy visualization & downstream analysis for Bench scientists.
                                ![scdehashR](https://user-images.githubusercontent.com/22992035/182950664-c8b81e6e-d518-447a-aaf7-3c003123117a.gif)


## Table of Contents

- [Template](#team-repo-template)
    - [Background](#Background)
    - [Example Data](#Example Data)
    - [Usage](#usage)
        - [Installation](#installation)
        - [Dependecies](#requirements)
    - [Results](#results) _Optional depending on project_
    - [Team Members](#team-members)

## Background

Analysis of cost effective methods spawned techniques like CITE-Seq that pool samples from different experimental conditions/replicates/library preps which are sequenced to get a high throughput. There are tools like Seurat (Sajita Lab - https://satijalab.org/seurat/articles/hashing_vignette.html) who already developed a method (HTODemux) that can demultiplex pooled samples. So, through this Shiny app, we will be making it easy for anyone in the field of omics to QC, Demultiplex, Visualize, normalize and perform some downstream analysis.



## Example Data

Summary of the Study:

Study show that modified vaccinia Ankara (MVA)-based COVID-19 vaccine expressing membrane anchored pre-fusion stabilized spike (MVA/S) induces both neutralizing antibodies and CD8+ T cells in the blood and lung and protects from SARS-CoV-2 challenge. Single-cell RNA sequencing analysis of lung cells at day 4 post-infection revealed that MVA/S vaccination also protected macaques from infection-induced inflammation and B cell abnormalities, and lowered induction of interferon stimulated genes.

(https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE165747)

## Usage

### Installation

Install Rstudio and install Rshiny package. We will provide the github link to the app, which can be installed using the following commands:

```sh
install.packages("devtools")
install_github("scDehashR")
```
Once you start the app, it should open up a Rshiny pop-up window (allow pop-up on your internet browser) which can be used to load and analyze the data.

### Requirements

*OS:*

Works on Mac, windows and Linux (gui)

*R Libaries required:*

Seurat
dplyr
plotly
ggplot2
clusterprofiler
knitr
kableExtra
cowplot
gridExtra
tidyverse
biomaRt
Matrix
stringr
DoubletFinder (optional)
SingleR (optional - Cell annotation Tool)

## Results

Need to be posted yet.

## Team Members

Arun Boddapati | arunbodd@outlook.com | Team Leader  
Srinivas Nallandighal |  srinivasnvnk55@gmail.com | Team Member
Ojonugwa Abubakar |  Otabu01@gmail.com | Team Member
JaMor Hairston | jmhairs@uab.edu | Team Member
Jason Needham | jneedham@uab.edu | Team Member
Aaron Lynch | aaron.lynch24@gmail.com | Team Member
Antony Linto | lintoantony@uabmc.edu | Team Member
