+++
title = "Robustness and applicability of functional genomics tools on scRNA-seq data"
date = "2020-02-12"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["Christian H. Holland","Jovan Tanevski","Javier Perales-Patón","Jan Gleixner","Manu P. Kumar","**Elisabetta Mereu**","Brian A. Joughin","Oliver Stegle","Douglas A. Lauffenburger","Holger Heyn","Bence Szalai","Julio Saez-Rodriguez"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Robustness and applicability of functional genomics tools on scRNA-seq data"
publication_short = ""


# Abstract and optional shortened version.
abstract = "Background: Many functional analysis tools have been developed to extract functional and mechanistic insight from bulk transcriptome data. With the advent of single-cell RNA sequencing (scRNA-seq), it is in principle possible to do such an analysis for single cells. However, scRNA-seq data has characteristics such as drop-out events and low library sizes. It is thus not clear if functional TF and pathway analysis tools established for bulk sequencing can be applied to scRNA-seq in a meaningful way. Results: To address this question, we perform benchmark studies on simulated and real scRNA-seq data. We include the bulk-RNA tools PROGENy, GO enrichment, and DoRothEA that estimate pathway and transcription factor (TF) activities, respectively, and compare them against the tools SCENIC/AUCell and metaVIPER, designed for scRNA-seq. For the in silico study, we simulate single cells from TF/pathway perturbation bulk RNA-seq experiments. We complement the simulated data with real scRNA-seq data upon CRISPR-mediated knock-out. Our benchmarks on simulated and real data reveal comparable performance to the original bulk data. Additionally, we show that the TF and pathway activities preserve cell type-specific variability by analyzing a mixture sample sequenced with 13 scRNA-seq protocols. We also provide the benchmark data for further use by the community. Conclusions: Our analyses suggest that bulk-based functional analysis tools that use manually curated footprint gene sets can be applied to scRNA-seq data, partially outperforming dedicated single-cell tools. Furthermore, we find that the performance of functional analysis tools is more sensitive to the gene sets than to the statistic used."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = ""
url_preprint = "https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-1949-z"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
[[url_custom]]
name = "Journal"
url = "https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-1949-z"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true
  
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = ""
#caption = "My caption :smile:"

+++


