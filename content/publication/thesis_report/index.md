---
title: "Self-supervised Learning for Sonar Images: Enhancing Multimodal Perception for Underwater Applications"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-12-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-10-02T00:00:00Z"
publishDate: "2021-09-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: Master Thesis Report, Department of Computer Science, Hochschule Bonn-Rhein-Sieg University of Applied Sciences 
publication_short: Master Thesis Report, Department of Computer Science, Hochschule Bonn-Rhein-Sieg University of Applied Sciences 

abstract: Machine perception in autonomous underwater systems is a very challenging task due to the unpredictability of water environments. Factors such as poor lighting conditions, sediments, and turbidity impact the vision of underwater systems and can result in failure of critical localization and exploration missions. In order to overcome underwater perception challenges, it is important to design computer vision models that can perform efficiently across a variety of tasks including image classification and image enhancement (reconstruction/generation). The advent of deep neural networks and their success on computer vision tasks applied to standard RGB images makes them suitable for underwater perception research. In recent years, deep neural network architectures have proved to be successful at underwater applications like image enhancement, sonar object classification, and multimodal sonar-camera image translation. For underwater sonar data specifically, the progress of deep learning research has been hindered due to the lack of publicly available data. This has to do with the confidentiality that surrounds sonar imaging projects. In order to compensate for small datasets and lack of annotated data, a novel learning paradigm called self-supervised learning (SSL) attempts to learn data representations by using data itself as a supervision signal. In this work, we apply self-supervised learning on sonar images with applications to image classification and image-to-image translation. For sonar image classification, we have implemented three SSL algorithms (RotNet, Denoising Autoencoders, and Jigsaw Puzzle) and compared them to their supervised learning (SL) counterpart. We have trained each of these models on a real-life sonar dataset called Watertank and evaluated the quality of the learned representations with transfer learning and a low-shot setup on another real-life sonar dataset called Turntable. Our findings indicate that all SSL models have a similar performance against SL models. This indicates that SSL has the potential to replace the need for labeled sonar datasets without compromising task performance and reducing the time and costs of data labeling. For multimodal sonar and camera image translation, we present results on a newly generated dataset called Gemini that contains paired sonar and camera images from different objects placed under the water. We have implemented the Pix2Pix model which is a type of conditional Generative Adversarial Network (cGAN) that is capable of combining sonar-camera modalities to generate realistic camera-like images. Based on several quantitative evaluations for image similarity, we prove that a combination of sonar and camera modalities improves image generation when compared to a single camera modality. This has the potential to aid underwater perception when light attenuation and turbidity affects cameras considerably.

# Summary. An optional shortened abstract.
summary: In this work, we apply self-supervised learning on sonar images with applications to image classification and image-to-image translation.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1lbArNMaFJpAPIuT45Q1XdrlgxuLAG8ye/view'
url_code: 'https://github.com/agrija9/master_thesis'
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
