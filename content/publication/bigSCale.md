+++
title = "bigSCale: An Analytical Framework for Big-Scale Single-Cell Data"
date = "2018-05-03"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.


authors = ["Giovanni Iacono","**Elisabetta Mereu**","Amy Guillaumet-Adkins","Roser Corominas","Ivon Cuscó","Gustavo Rodríguez-Esteban","Marta Gut","Luis Alberto Pérez-Jurado","Ivo Gut","Holger Heyn"]



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
publication = "*bigSCale: An Analytical Framework for Big-Scale Single-Cell Data"
publication_short = ""


# Abstract and optional shortened version.
abstract = "Single-cell RNA sequencing (scRNA-seq) has significantly deepened our insights into complex tissues, with the latest techniques capable of processing tens of thousands of cells simultaneously. Analyzing increasing numbers of cells, however, generates extremely large data sets, extending processing time and challenging computing resources. Current scRNA-seq analysis tools are not designed to interrogate large data sets and often lack sensitivity to identify marker genes. With bigSCale, we provide a scalable analytical framework to analyze millions of cells, which addresses the challenges associated with large data sets. To handle the noise and sparsity of scRNA-seq data, bigSCale uses large sample sizes to estimate an accurate numerical model of noise. The framework further includes modules for differential expression analysis, cell clustering, and marker identification. A directed convolution strategy allows processing of extremely large data sets, while preserving transcript information from individual cells. We evaluated the performance of bigSCale using both a biological model of aberrant gene expression in patient-derived neuronal progenitor cells and simulated data sets, which underlines the speed and accuracy in differential expression analysis. To test its applicability for large data sets, we applied bigSCale to assess 1.3 million cells from the mouse developing forebrain. Its directed down-sampling strategy accumulates information from single cells into index cell transcriptomes, thereby defining cellular clusters with improved resolution. Accordingly, index cell clusters identified rare populations, such as reelin (Reln)-positive Cajal-Retzius neurons, for which we report previously unrecognized heterogeneity associated with distinct differentiation stages, spatial organization, and cellular function. Together, bigSCale presents a solution to address future challenges of large single-cell data sets."

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
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = "https://genome.cshlp.org/content/28/6/878.short"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
[[url_custom]]
name = "Journal"
url = "https://genome.cshlp.org/content/28/6/878.short"

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


