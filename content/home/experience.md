---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Senior Scientist
    company: Morphic Therapeutic
    company_url: 'https://morphictx.com/'
    # company_logo: org-gc
    location: Massachusetts, USA
    date_start: '2021-07-01'
    date_end: ''
    description: Develop or apply new tools, algorithms, and data mining techniques for the integrative analysis of large genomic datasets for use in the development of oral integrin therapies.
        
  - title: Postdoctoral Fellow
    company: Massachusetts General Hospital & Harvard Medical School​
    company_url: 'https://www.massgeneral.org/'
    # company_logo: org-x
    location: Massachusetts, USA
    date_start: '2018-09-01'
    date_end: '2021-07-01'
    description: |2-
        * Developed single cell embedding method [SIMBA](https://simba-bio.readthedocs.io/) for the co-embeddings of cells and features
        * Developed single cell omics trajectory inference tool [STREAM](https://github.com/pinellolab/STREAM).
        * Benchmarked the performances of single-cell trajectory inference tools based on topology correctness and pseudotime accuracy
        * Developed single cell Virtual Reality tool [​singlecellVR](https://singlecellvr.pinellolab.partners.org/) with Dash by plotly and A-Frame


  - title: Postdoctoral Fellow
    company: Broad Institute Of MIT And Harvard
    company_url: 'https://www.broadinstitute.org/'
    # company_logo: org-x
    location: Massachusetts, USA
    date_start: '2019-02-01'
    date_end: '2021-07-01'
    description: |2-
        * Provided the first systematic [single cell ATAC-seq computational method benchmarking](https://github.com/pinellolab/scATAC-benchmarking) study.
        * Assessed ten scATAC-seq computational pipelines and created a valuable resource for scATAC-seq study with more than 100 well-documented Jupyter notebooks
        * Implemented XGBboost to solve regression problem for predicting gene expression level from scATAC-seq analysis


  - title: Research Assistant
    company: Massachusetts General Hospital & Harvard Medical School​
    company_url: 'https://www.massgeneral.org/'
    # company_logo: org-x
    location: Massachusetts, USA
    date_start: '2016-10-01'
    date_end: '2018-08-01'
    description: |2-
      * Contributed to a scalable unsupervised structure learning method *​ElPiGraph*​ for approximating complex topologies via principal graph
      * Performed and benchmarked various clustering analyses for cell type identification
      * Performed and benchmarked various dimensionality reduction methods for single-cell visualization
      * Developed statistical hypothesis testing methods for single-cell marker detection

  - title: Research Scholar
    company: Dana-Farber Cancer Institute​ & Harvard T.H. Chan School of Public Health
    company_url: 'https://www.massgeneral.org/'
    # company_logo: org-x
    location: Massachusetts, USA
    date_start: '2015-09-01'
    date_end: '2017-09-01'
    description: |2-
        * Co-developer of a Gini-index-based novel computational method ​[GiniClust](https://github.com/lanjiangboston/GiniClust)​ to detect rare cells using the density-based clustering method DBSCAN
        * Performed single cell RNA-seq trajectory inference analysis to dissect hematopoietic and renal cell heterogeneity in adult zebrafish
        * Performed single-cell RNA-seq dataset alignment across experiments for human pluripotent stem cells early differentiation study

  - title: Graduate researcher
    company: Tongji University​
    company_url: 'https://en.tongji.edu.cn/'
    # company_logo: org-x
    location: Shanghai, China
    date_start: '2012-09-01'
    date_end: '2015-09-01'
    description: |2-
        * Developed a Bayesian-nonparametric-modeling-based novel approach ​*DPNuc*​ for identifying nucleosome positions using the Dirichlet process mixture model
        * Applied Markov chain Monte Carlo (MCMC) simulations to estimate the parameters

  - title: Teaching Assistant
    company: Tongji University​
    company_url: 'https://en.tongji.edu.cn/'
    # company_logo: org-x
    location: Shanghai, China
    date_start: '2012-09-01'
    date_end: '2013-06-01'
    description: Led hands-on SQL language sessions and taught students how to access and manipulate databases. Taught weekly sections, held office hours, and assisted with grading homework and exams.

  - title: Purchasing Intern
    company: Faurecia
    company_url: 'https://www.faurecia.com/'
    # company_logo: org-x
    location: Shanghai, China
    date_start: '2011-10-01'
    date_end: '2011-11-01'
    description: Processed office forms and maintained the database of orders to assist with purchasing tasks.

design:
  columns: '2'
---
