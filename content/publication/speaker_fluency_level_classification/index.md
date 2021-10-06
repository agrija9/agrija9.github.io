---
title: "Speaker Fluency Level Classification Using Machine Learning Techniques"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Ramon F. Brena

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2018-08-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-08-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: arXiv preprint
publication_short: arXiv preprint

abstract: 
  Level assessment for foreign language students is necessary for putting them in the right level group, furthermore, interviewing students is a very time-consuming task, so we propose to automate the evaluation of speaker fluency level by implementing machine learning techniques. This work presents an audio processing system capable of classifying the level of fluency of non-native English speakers using five different machine learning models. As a first step, we have built our own dataset, which consists of labeled audio conversations in English between people ranging in different fluency domains/classes (low, intermediate, high). We segment the audio conversations into 5s non-overlapped audio clips to perform feature extraction on them. We start by extracting Mel cepstral coefficients from the audios, selecting 20 coefficients is an appropriate quantity for our data. We thereafter extracted zero-crossing rate, root mean square energy and spectral flux features, proving that this improves model performance. Out of a total of 1424 audio segments, with 70% training data and 30% test data, one of our trained models (support vector machine) achieved a classification accuracy of 94.39%, whereas the other four models passed an 89% classification accuracy threshold.

# Summary. An optional shortened abstract.
summary: This work presents an audio processing system capable of classifying the level of fluency of non-native English speakers using five different machine learning models. As a first step, we have built our own dataset, which consists of labeled audio conversations in English between people ranging in different fluency domains/classes (low, intermediate, high).

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1808.10556.pdf'
url_code: 'https://github.com/agrija9/Avalinguo-Dataset-Speaker-Fluency-Level-Classification-Paper-'
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
