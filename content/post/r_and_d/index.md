---
title: "Generative Models for the Analysis of Dynamical Systems with Applications"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-10-02T00:00:00Z"

doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-02T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: Technical Report/Hochschule Bonn-Rhein-Sieg University of Applied Sciences, Department of Computer Science
publication_short: Technical Report/Hochschule Bonn-Rhein-Sieg University of Applied Sciences, Department of Computer Science

abstract: 
High-dimensional and multi-variate data from dynamical systems such as turbulent flows and wind
turbines can be analyzed with deep learning due to its capacity to learn representations in lower-dimensional
manifolds. Two challenges of interest arise from data generated from these systems, namely, how to
anticipate wind turbine failures and how to better understand air flow through car ventilation systems.
There are deep neural network architectures that can project data into a lower-dimensional space
with the goal of identifying and understanding patterns that are not distinguishable in the original
dimensional space. Learning data representations in lower dimensions via non-linear mappings allows one
to perform data compression, data clustering (for anomaly detection), data reconstruction and synthetic
data generation.
In this work, we explore the potential that variational autoencoders (VAE) have to learn low-dimensional
data representations in order to tackle the problems posed by the two dynamical systems mentioned above.
A VAE is a neural network architecture that combines the mechanisms of the standard autoencoder and
variational bayes. The goal here is to train a neural network to minimize a loss function defined by a
reconstruction term together with a variational term defined as a Kulback-Leibler (KL) divergence.
The report discusses the results obtained for the two different data domains$:$ wind turbine time series
and turbulence data from computational fluid dynamics (CFD) simulations.
We report on the reconstruction, clustering and unsupervised anomaly detection of wind turbine
multi-variate time series data using a variant of a VAE called Variational Recurrent Autoencoder (VRAE).
We trained a VRAE to cluster normal and abnormal wind turbine series (two class problem) as well
as normal and multiple abnormal series (multi-class problem). We found that the model is capable of
distinguishing between normal and abnormal cases by reducing the dimensionality of the input data
and projecting it to two dimensions using techniques such as Principal Component Analysis (PCA) and
t-distributed stochastic neighbor embedding (t-SNE). A set of anomaly scoring methods is applied on top
of these latent vectors in order to compute unsupervised clustering. We have achieved an accuracy of up
to 96% with the KM eans + + algorithm.
We also report the data reconstruction and generation results of two dimensional turbulence slices
corresponding to CFD simulation of a HVAC air duct. For this, we have trained a Convolutional
Variational Autoencoder (CVAE). We have found that the model is capable of reconstructing laminar
flows up to a certain degree of resolution as well generating synthetic turbulence data from the learned
latent distribution.

# Summary. An optional shortened abstract.
summary: The report discusses the results obtained for the two different data domains$:$ wind turbine time series
and turbulence data from computational fluid dynamics (CFD) simulations.
We report on the reconstruction, clustering and unsupervised anomaly detection of wind turbine
multi-variate time series data using a variant of a VAE called Variational Recurrent Autoencoder (VRAE).


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1kExl70eXunww9F64kPq7h28cN4oee007/view?usp=sharing'
url_code: 'https://github.com/agrija9/r-d_project'
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
