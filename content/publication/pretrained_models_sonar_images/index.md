---
title: "Pre-trained Models for Sonar Images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Matias Valdenegro-Toro
- admin
- Bilal Wehbe

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-08-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Global OCEANS
publication_short: OCEANS

# abstract: Machine learning and neural networks are now ubiquitous in sonar perception, but it lags behind the computer vision field due to the lack of data and pre-trained models specifically for sonar images. In this paper we present the Marine Debris Turntable dataset and produce pre-trained neural networks trained on this dataset, meant to fill the gap of missing pre-trained models for sonar images. We train Resnet 20, MobileNets, DenseNet121, SqueezeNet, MiniXception, and an Autoencoder, over several input image sizes, from 32 x 32 to 96 x 96, on the Marine Debris turntable dataset. We evaluate these models using transfer learning for low-shot classification in the Marine Debris Watertank and another dataset captured using a Gemini 720i sonar. Our results show that in both datasets the pre-trained models produce good features that allow good classification accuracy with low samples (10-30 samples per class). The Gemini dataset validates that the features transfer to other kinds of sonar sensors. We expect that the community benefits from the public release of our pre-trained models and the turntable dataset. 

# Summary. An optional shortened abstract.
summary: In this paper we present the Marine Debris Turntable dataset and produce pre-trained neural networks trained on this dataset, meant to fill the gap of missing pre-trained models for sonar images. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2108.01111'
url_code: 'https://github.com/mvaldenegro/pretrained-models-sonar-images/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Sonar pipe'
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
