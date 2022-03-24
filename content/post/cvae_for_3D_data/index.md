---
title: "Training a Convolutional Variational Autoencoder on 3D CFD Turbulence Data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-10-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-10-02T00:00:00Z"
publishDate: "2022-09-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: Medium
publication_short: Medium

abstract: In this project we implement a Convolutional Variational Autoencoder (CVAE) to process and reconstruct 3D turbulence data. We have generated 3D turbulence cubes using Computational Fluid Dynamics (CFD) methods, each 3D cube carries physical information along three velocity components (treated as separate channels in analogy to image data). As part of 3D CFD data pre-processing, we have written a custom pytorch dataloader that performs normalization and batching operations on the dataset. The CVAE implements 3D Convolutions (3DConvs) on the pre-processed data to perform reconstruction. We have obtained substantial improvement on 3D reconstruction by fine-tunning hyper-parameters and manipulating our model architecture.

# Summary. An optional shortened abstract.
summary: In this project we implement a Convolutional Variational Autoencoder (CVAE) to process and reconstruct 3D turbulence data. We have generated 3D turbulence cubes using Computational Fluid Dynamics (CFD) methods, each 3D cube carries physical information along three velocity components (treated as separate channels in analogy to image data). As part of 3D CFD data pre-processing, we have written a custom pytorch dataloader that performs normalization and batching operations on the dataset. The CVAE implements 3D Convolutions (3DConvs) on the pre-processed data to perform reconstruction. We have obtained substantial improvement on 3D reconstruction by fine-tunning hyper-parameters and manipulating our model architecture.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://medium.com/@agrija9/training-a-convolutional-variational-autoencoder-on-3d-cfd-turbulence-data-7df8e207a58f'
url_code: 'https://github.com/agrija9/Convolutional-VAE-for-3D-Turbulence-Data'
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
