---
title: "SIMBA: SIngle-cell eMBedding Along with features"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jayoung Ryu
- Michael E Vinyard
- Adam Lerer
- Luca Pinello


# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-05-29"
# doi: "10.1038/s41467-019-09670-4"

# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Nature Methods
# publication_short: 

abstract: Most current single-cell analysis pipelines are limited to cell embeddings and rely heavily on clustering, while lacking the ability to explicitly model interactions between different feature types. Furthermore, these methods are tailored to specific tasks, as distinct single-cell problems are formulated differently. To address these shortcomings, here we present SIMBA, a graph embedding method that jointly embeds single cells and their defining features, such as genes, chromatin-accessible regions and DNA sequences, into a common latent space. By leveraging the co-embedding of cells and features, SIMBA allows for the study of cellular heterogeneity, clustering-free marker discovery, gene regulation inference, batch effect removal and omics data integration. We show that SIMBA provides a single framework that allows diverse single-cell problems to be formulated in a unified way and thus simplifies the development of new analyses and extension to new single-cell modalities. SIMBA is implemented as a comprehensive Python library (https://simba-bio.readthedocs.io).

# Summary. An optional shortened abstract.
summary: SIMBA is a method to embed cells along with their defining features such as gene expression, transcription factor binding sequences and chromatin accessibility peaks into the same latent space. The joint embedding of cells and features allows SIMBA to perform various types of single cell tasks, including but not limited to single-modal analysis (e.g. scRNA-seq and scATAC-seq analysis), multimodal analysis, batch correction, and multi-omic integration.

tags: [Single-cell, scRNA-seq, scATAC-seq, Graph Embedding, Dimensionality Reduction, PyTorch, Batch Corrction, Multiomics Integration, Multimodal]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.nature.com/articles/s41592-023-01899-8.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'SIMBA'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
