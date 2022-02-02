---
title: "Single-cell trajectories reconstruction, exploration and mapping of omics data with STREAM"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jihong Guan
- Shuigeng Zhou

# # Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2015-05-25"
doi: "10.1109/TCBB.2015.2430350"

# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE/ACM Transactions on Computational Biology and Bioinformatics
publication_short: TCBB

abstract: Nucleosomes and the free linker DNA between them assemble the chromatin. Nucleosome positioning plays an important role in gene transcription regulation, DNA replication and repair, alternative splicing, and so on. With the rapid development of ChIP-seq, it is possible to computationally detect the positions of nucleosomes on chromosomes. However, existing methods cannot provide accurate and detailed information about the detected nucleosomes, especially for the nucleosomes with complex configurations where overlaps and noise exist. Meanwhile, they usually require some prior knowledge of nucleosomes as input, such as the size or the number of the unknown nucleosomes, which may significantly influence the detection results. In this paper, we propose a novel approach DPNuc for identifying nucleosome positions based on the Dirichlet process mixture model. In our method, Markov chain Monte Carlo (MCMC) simulations are employed to determine the mixture model with no need of prior knowledge about nucleosomes. Compared with three existing methods, our approach can provide more detailed information of the detected nucleosomes and can more reasonably reveal the real configurations of the chromosomes; especially, our approach performs better in the complex overlapping situations. By mapping the detected nucleosomes to a synthetic benchmark nucleosome map and two existing benchmark nucleosome maps, it is shown that our approach achieves a better performance in identifying nucleosome positions and gets a higher F-score. Finally, we show that our approach can more reliably detect the size distribution of nucleosomes.

# Summary. An optional shortened abstract.
# summary: An interactive pipeline capable of disentangling and visualizing complex branching trajectories from both single-cell transcriptomic and epigenomic data.

tags: [Nucleosome Positioning, Epigenome, Dirichlet Process, Markov Chain Monte Carlo, MNase-seq]

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
