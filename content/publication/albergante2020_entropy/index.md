---
title: "Robust and scalable learning of complex intrinsic dataset geometry via ElPiGraph"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Luca Albergante
- Evgeny Mirkes
- Jonathan Bac
- admin
- Alexis Martin
- Louis Faure
- Emmanuel Barillot
- Luca Pinello
- Alexander Gorban
- Andrei Zinovyev

# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-03-04"
doi: "10.3390/e22030296"

# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Entropy
publication_short: Entropy

abstract: Multidimensional datapoint clouds representing large datasets are frequently characterized by non-trivial low-dimensional geometry and topology which can be recovered by unsupervised machine learning approaches, in particular, by principal graphs. Principal graphs approximate the multivariate data by a graph injected into the data space with some constraints imposed on the node mapping. Here we present ElPiGraph, a scalable and robust method for constructing principal graphs. ElPiGraph exploits and further develops the concept of elastic energy, the topological graph grammar approach, and a gradient descent-like optimization of the graph topology. The method is able to withstand high levels of noise and is capable of approximating data point clouds via principal graph ensembles. This strategy can be used to estimate the statistical significance of complex data features and to summarize them into a single consensus principal graph. ElPiGraph deals efficiently with large datasets in various fields such as biology, where it can be used for example with single-cell transcriptomic or epigenomic datasets to infer gene expression dynamics and recover differentiation landscapes.

# # Summary. An optional shortened abstract.
# summary: An interactive pipeline capable of disentangling and visualizing complex branching trajectories from both single-cell transcriptomic and epigenomic data.

tags: [Principal Graph, Data Approximation, Principal Trees, Topological Grammars]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: ''
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
