---
title: "Project report template"
output:
  html_document:
    keep_md: true
    toc: true
    toc_depth: 3
    code_folding: show
  pdf_document: default
---

<style>

body,p,h1,h2,h3,h4,h5,h6 {
  text-align: justify;
  color: #424949;
  font-weight: 400;
  font-size: 14px;
  line-height: 1.55;}

h1 {  font-size: 1.4em;font-weight: bold; }
h2 {  font-size: 1.2em;font-weight: bold; }
h3 {  font-size: 1.1em;font-weight: bold; }
h4 {  font-size: 1.0em;font-weight: bold; }

pre {
  font-family: "Courier";
  background-color: #F7F7F7;
  border: 1px solid #CCCCCC;
  font-size: 14px;}

code {
  font-family: "Courier New";
  font-size: 14px;
  word-break: break-all;
  font-weight: bold;}

</style>



# Research Analysis Tasks:

## Milestone 1

####	Find and download suitable datasets to work
- Consult the Glossary for help
- Go to PanglaoDB and look for an appropriate dataset:
- Which species should it be?
- For this tutorial, please use 10X Chromium datasets only
- For this tutorial, please limit the amount of cells to about 10000 cells
- Describe in form of text the rational for this step in your markdown report.


####	Load and merge datasets
- Consult the Glossary for help
- which file format do we have the data in?
- Why do we need to create a seurat object?
- Describe in form of text the rational for this step in your markdown report.


####	Compute QC
- Consult the Glossary for help
- Which QC metrics should I calculate?
- What does each QC metric mean?
- Describe in form of text the rational for this step in your markdown report.


####	Define appropriate filtering thresholds
- Consult the Glossary for help
- Which QC metric needs filtering?
- Why use median and not mean?
- Which quantile should I use?
- Describe in form of text the rational for this step in your markdown report.



## Milestone 2

⁃	Integrate datasets
⁃	Filter noise from data
⁃	Visualize data (look for the appropriate dim reduction)
⁃	Control for confounding variables (cell cycle and ribosomal/mitochondrial percentage)


## Milestone 3

⁃	Check for batch effects
⁃	Construct graph
⁃	Perform clustering

## Milestone 4

⁃	Perform differential gene expression among clusters
⁃	Identify cell types of interest
⁃	Check your cell types with the known biology of cell differentiation in BM


## Milestone 5 (optional)

⁃	Build trajectory embedding (change embedding variables, so you have a continuous path)
⁃	Define lineages
⁃	Visualize lineages
⁃	Perform differential expression on the desired branches
⁃	Report the best gene candidates for each population











