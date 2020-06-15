# single-cell-pbl
Single Cell Project Based Learning (PBL)


The idea is to learn-by-doing, using the [**Project_report_template**](Project_report_template.md) (download `.Rmd` file: [**.Rmd**](Project_report_template.Rmd))  [**Glossary of concepts**](Glossary_of_concepts.md) as guide to find and discuss advanced topics with your team mates, construct rational anlaysis decisions and build knowledge thought active learning.

<br/>

##### Experience level required:

-	R & Rmarkdown
-	RNAseq analysis experience 

<br/>

#### Time:

⁃	2.5 days (3 x 12h)

<br/>

#### Project #1:

**Background**

Ulcerative colitis (UC) is an inflammatory bowel disease (IBD) driven mainly by colonic innate inflammatory cells such as macrophages, monocytes and neutrophils (Czarnewski 2019, Skatteborg 2020). A recent study showed that patients that present higher neutrophilic/monocytic inflammatory signature (known as UC1) become refractory to both anti-TNF and anti-a4b7 integrin therapy (Czarnewski 2019, Skatteborg 2020), which leads to surgical intervention for removal of the colon. Both of these inflammatory cells are short lived and originate from the common myeloid progenitor (CMP) in the bone marrow and requires constant replenishment in order to sustain elevated cell number in the colon. Herein, our main goal is to identify potential gene candidates that can block either one or both pathways of neutrophil and monocyte differentiation in the bone marrow.

**Main research question**

Which genes specifically drive the differentiation of 1) common myeloid progenitors, 2) Monocytes and 3) Neutrophils. (optional)

**Importance**

Identifying such genes will allow us to: 1) perform experiment in Tamoxifen-transgenic mice where those cells can be depleted during the course of colitis. 2) find potential drugs that can inhibit those genes/pathways in order to block myeloid cell differentiation during colitis in mice (with priority to already approved drugs).

<br/>

#### Project #2:

**Background**

N/A

**Main research question**

N/A

**Importance**

N/A

<br/>

#### Learning Outcomes:

⁃	Be able to get and load datasets ( h5, mtx, SS2 )
⁃	Be able to use and compute QC metics
⁃	Be able to use and define sensible filtering thresholds
⁃	Be able to use and distinguish dataset integration methods ( MNN , CCA )
⁃	Be able to use and distinguish dimensionality reduction methods for different tasks (PCA, UMAP, tSNE, DM)
⁃	How the different parameters influence your interpretation?
⁃	Be able to construct graphs from data (kNN and SNN)
⁃	Be able to use and distinguish clustering techniques ( Louvain , HC , kmeans )
⁃	Be able to construct meaningful trajectories (Slingshot)

<br/>

#### Research Analysis Tasks:

**Milestone 1**

⁃	Find and download suitable datasets to work with (or provide the datasets)
⁃	Load and merge datasets
⁃	Define appropriate filtering thresholds

**Milestone 2**

⁃	Integrate datasets
⁃	Filter noise from data
⁃	Visualize data (look for the appropriate dim reduction)
⁃	Control for confounding variables (cell cycle and ribosomal/mitochondrial percentage)

**Milestone 3**

⁃	Check for batch effects
⁃	Construct graph
⁃	Perform clustering

**Milestone 4**

⁃	Perform differential gene expression among clusters
⁃	Identify cell types of interest
⁃	Check your cell types with the known biology of cell differentiation in BM


**Milestone 5 (optional)**

⁃	Build trajectory embedding (change embedding variables, so you have a continuous path)
⁃	Define lineages
⁃	Visualize lineages
⁃	Perform differential expression on the desired branches
⁃	Report the best gene candidates for each population


<br/>

#### Staying On Task During Project-Based Learning
Usage of boards to define tasks

<br/>

#### Grading
Documentation reporting the steps and justifying the decisions in the analysis

<br/>

#### Challenges
-	Time 12 h
-	How to make the group work collaboratively (1 report, but 4 people working in their Rstudio)
-	How to divide tasks (reporting, writing code, testing, etc)

<br/>

#### Glossary of terms
-	Create a glossary that the students can refer to and use as guide
-	Maybe later create the general glossary with the main text concepts (but can be imported into the specify glossaries for each course)

<br/>

#### Reference Material:
https://www.edutopia.org/video/5-keys-rigorous-project-based-learning
https://www.edutopia.org/article/project-based-learning-and-research-paper
https://www.edutopia.org/video/staying-task-during-project-based-learning
https://www.edutopia.org/article/3-common-pbl-problems-and-solutions




