---
title: Benchmarking scRNA-seq protocols for cell atlas projects.
summary: In this study we systematically compared 13 scRNA-seq protocols in many aspects that are relevant for cell atlas projects.
tags:
- Internal
date: "2020"

# Optional external URL for project (replaces project detail page).
external_link: "https://www.nature.com/articles/s41587-020-0469-4"
#external_link: "https://bioengineeringcommunity.nature.com/users/365693-joshua-levin/posts/65108-tbd"

# image:
 #  caption: Tsnes
  # focal_point: Smart

# links:
# - icon: twitter
 #  icon_pack: fab
  # name: Follow
  url: https://bioengineeringcommunity.nature.com/users/365693-joshua-levin/posts/65108-tbd 
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Single-cell RNA-seq (scRNA-seq) is successfully applied to dissect the cellular composition of tissues and organs. As a result, last years were characterized by an explosion of both data and new protocols in order to strengthen the technological advance of scRNA-seq. In this context, the Human Cell Atlas project first and other similar international initiatives later aim to create a catalogue of all cell types in the human body. 
However the transcriptomic analysis of individual cells presents a number of technical and computational challenges which makes this ambitious goal difficult. The first challenge is related to the experimental design and the choice of the protocol most suitable for the biological sample based on the questions that experiment intends to answer. While the number of proposed protocols is huge and the field is still under development, none of them will probably meets all the needs. Each method has its own characteristics and their combination will be important to have a comprehensive view of the cellular map. It is crucial to be aware of technical confounders in order to create results that are reproducible and with similar compositions other than serve as reference maps. For these reasons, a set of standards and guidelines is necessary and will guide toward a better design of the atlas.

In our study titled “Benchmarking single-cell RNA sequencing methods”, we focused on the systematic comparison of the most common protocols, highlighting many aspects that are important for cell atlas projects. The key idea of the project was to define a controlled experiment, by the creation of a complex biological sample, consisting of a mixture of species and tissues of known proportions. The sample was prepared in a single batch and then sent to 13 centers, which analyzed it following their own sequencing protocol. Following, we uniformly processed data through the same pipeline which was adapted ad hoc for the sample. 

The unified sample included the three species human (66%), mouse (33%) and dog (1%). While human cells contained mostly PBMC (60%), which were from four different donors and HEK293 cells, mouse cells were from the colon (30%) and a smaller proportion of  NIH3H cells (3%). The use of more species and cell lines allowed us to account for the integrity of the sample in each protocol. Further, the choice of PBMC and colon tissues was aiming to simulate two typical scenarios of single cell projects. In both cases, the cellular structure of these tissues is complex, consisting in a wide range of cell types and states having specific characteristics. Cell types of different sizes and a different grade of intra-cellular heterogeneity were expected, allowing to rank the protocols in their abilities of recapitulate the original sample.

For the identification of cell types, each protocol was first analyzed separately, through clustering and the identification of cluster-specific gene markers. Then datasets were aligned to a common set of cell annotations which was based on a large-scale reference dataset (40K cells for human and 30K for mouse), created with the same experimental sample. In this way, we could fairly compare same identified cell types in many different properties reflecting the protocol performance. 

Importantly, we systematically compared protocols in their sensitivity to detect genes and accuracy in gene measurements. Pairwise correlations in the levels of expression of the full transcriptome as well as in cell type specific markers were also compared in different cell types. 

While these measures are commonly used to quantify technical performances of sequencing methods, we additionally considered other metrics that are of interest for atlas projects. Indeed, differences in gene detection sensitivity and accuracy could impact differently in the downstream analysis. Therefore we considered the typical computational tasks for single cell data and scored protocols in their abilities to accomplish them.

The ability of recover cell types through clustering analysis (clusterability) or the transferring of cell identities from a reference dataset (mappability) are essential to describe the cellular structure of a biological sample. Further, the integration of data from different protocols (integratability) is also fundamental, being the atlas the union of more datasets. Overall these abilities give a comprehensive evaluation of the most common protocols for scRNA-seq. 

While previous benchmarking of protocols were focused on comparative analysis in homogenous populations, we extended these studies by simulating complex scenarios and considering unconventional metrics that are especially important for consortia projects. With our study we provide an experimental framework that can be applied to other cell type mixtures to test future protocols and answer specific questions. A set of practical guidelines that are fundamental to design future studies were also supplied. Moreover, these datasets represent an important resource for the development and benchmarking of new computational tools specifically designed for the analysis of single cell data.


Data
All raw sequencing data and processed gene expression files are freely available through the Gene Expression Omnibus (GEO; GSE133549). All code is available under https://github.com/ati-lz/HCA_Benchmarking and  https://github.com/elimereu/matchSCore2 
