# scDehashR
The purpose of this app is to develop an interactive Shiny portal that can dehash any number of pooled samples from single cell techniques for easy visualization & downstream analysis for Bench scientists.
 
<p align="center">

 ![scDehashR (2)](https://user-images.githubusercontent.com/22992035/182951623-80e3b41e-1ac9-4f2b-98f5-b8a3aa906573.gif)

</p>

## Table of Contents
 - [Background](#background)
 - [Example Data](#exampledata)
 - [Usage](#usage)
     - [Installation](#installation)
     - [Dependecies](#requirements)
 - [Plan](#plan)
     - [Module-1](#module-1)
     - [Module-2](#module-2)
     - [Module-3](#module-3)
     - [Module-4](#module-4)
     - [Module-5](#module-5)
     - [Module-6](#module-6)
     - [Module-7](#module-7)
     - [Module-8](#module-8)
 - [Results](#results)
 - [Team Members](#team-members)

## Background

Analysis of cost effective methods spawned techniques like CITE-Seq that pool samples from different experimental conditions/replicates/library preps which are sequenced to get a high throughput. There are tools like Seurat (Sajita Lab - https://satijalab.org/seurat/articles/hashing_vignette.html); who already developed a method (HTODemux) that can demultiplex pooled samples. So, through this Shiny app, we will be making it easy for anyone in the field of omics to QC, Demultiplex, Visualize, normalize and perform downstream analysis for multiplex single-cell data.


## ExampleData

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

*R Libraries required:*

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

## Plan

Incudes Following Modules:

### Module-1

Quality Control - Visualization  

<p align="center">
 
 ![Example_QC_1](https://user-images.githubusercontent.com/22992035/182963897-e8983b6c-b3bb-4d63-b1e6-72d8815e73bf.png)

</p>

### Module-2

Demultiplexing and Doublet detection module – Visualization (optional)  

<p align="center">
 
 ![Example_QCmetrics](https://user-images.githubusercontent.com/22992035/182962598-05e561c1-576f-4c46-8b49-225029d37d9c.png)  
 
</p>


### Module-3 

Identifying Cell subset module by unsupervised learning – Visualization (UMAPS, TSNE, PCA, Elbow plot).  

<p align="center">

![Example_Umap_DehashedSamples](https://user-images.githubusercontent.com/22992035/182963974-89006d82-b05b-47ae-a070-a2141c8199e4.png)

</p>

### Module-4 

Integration – no visualization (background process – time taking step, dependent on no. of Capture or samples per capture or no. of cells in the experiment).  

### Module-5 

Differential expression module – Visualization (Heatmaps, RidgePlots, FeaturePlots, DotPlots).  

### Module-6

Gene set enrichment analysis module – Visualization (Upset plots, enrichment plots).  

### Module-7

Multi-gene set comparison module – Comparison of genes in Hallmark vs KEGG pathways.  

### Module-8

Visualization module – Additional plots like Marker genes expression across multiple treatment groups.  


## Results

Yet to be posted

## Team Members

Arun Boddapati | arunbodd@outlook.com | Team Leader  
Srinivas Nallandighal | srinivasnvnk55@gmail.com | Team Member  
Ojonugwa Abubakar | Otabu01@gmail.com | Team Member  
JaMor Hairston | jmhairs@uab.edu | Team Member  
Jason Needham | jneedham@uab.edu | Team Member  
Aaron Lynch | aaron.lynch24@gmail.com | Team Member  
Antony Linto | lintoantony@uabmc.edu | Team Member  
