---
title: "Anomaly Detection of Wind Turbine Time Series using Variational Recurrent Autoencoders"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Victor Rodrigo Iza-Teran

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-12-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: arXiv preprint
publication_short: arXiv preprint

abstract: 
   Ice accumulation in the blades of wind turbines can cause them to describe anomalous rotations or no rotations at all, thus affecting the generation of electricity and power output. In this work, we investigate the problem of ice accumulation in wind turbines by framing it as anomaly detection of multi-variate time series. Our approach focuses on two main parts, first, learning low-dimensional representations of time series using a Variational Recurrent Autoencoder (VRAE), and second, using unsupervised clustering algorithms to classify the learned representations as normal (no ice accumulated) or abnormal (ice accumulated). We have evaluated our approach on a custom wind turbine time series dataset, for the two-classes problem (one normal versus one abnormal class), we obtained a classification accuracy of up to 96% on test data. For the multiple-class problem (one normal versus multiple abnormal classes), we present a qualitative analysis of the low-dimensional learned latent space, providing insights into the capacities of our approach to tackle such problem. The code to reproduce this work can be found here this https URL. 

# Summary. An optional shortened abstract.
summary: In this work, we investigate the problem of ice accumulation in wind turbines by framing it as anomaly detection of multi-variate time series.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2112.02468'
url_code: 'https://github.com/agrija9/Wind_Turbines_VRAE_Paper'
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
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
slides: ""
---
