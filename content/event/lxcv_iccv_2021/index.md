---
title: Poster Presentation - LatinX in CV @ICCV2021

event: ICCV 2021 Conference
event_url: https://www.latinxinai.org/iccv-2021-about

location: Virtual (https://iccv2021.thecvf.com/)
address:
  street:
  city: 
  region: 
  postcode: 
  country:

summary: Testing.
abstract: "Neural networks have shown promising results in sonar
perception tasks such as object recognition [1], image
patch matching [2] and image classification [3]. In the
context of autonomous underwater vehicles, it is crucial
to develop robust, accurate and efficient models to
overcome the challenges of underwater perception.
In this work, we report progress on a comparative
evaluation of self-supervised learning (SSL) [6][7] and
supervised learning (SL) algorithms as pre-training
methods for sonar images. As a first step, we produce
pre-trained neural networks on the Marine Debris
Watertank Dataset [4] via a SSL method that classifies
image rotations [5] and a traditional SL approach to
classify the actual image labels. In both cases, we trained
a Resnet20, SqueezeNet, Mobilenet, DenseNet121 and
MiniXception on images of size 96x96. Thereafter, we
evaluate the quality of the learned features by using
transfer learning for low-shot classification on a target
dataset called Marine Debris Turntable [3].
The results presented in this poster indicate that the
SSL pre-trained models have a similar classification
performance compared to the SL counterpart across all
the neural network models. These results indicate that
SSL pre-training are a promising substitute for SL
methods without compromising object classification
and no need of human manual annotations.
Finally, we report on the creation of a new underwater
dataset that contains paired camera and sonar images
for different underwater objects (panels, cement pipes,
ladders, ramps). This dataset, called Gemini Sonar
Dataset, will allow us to perform further classification,
image translation and object detection tasks using SSL
approaches."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-10-11T13:00:00Z"
date_end: "2021-10-15T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2021-10-09T13:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
- icon: 
  icon_pack: 
  name: 
  url:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ""
-
---
