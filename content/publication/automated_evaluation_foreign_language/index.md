---
title: "Automated evaluation of foreign language speaking performance with machine learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ramon F. Brena
- Evelyn Zuvirie
- admin
- Aristh Valdiviezo
- Miguel Gonzalez-Mendoza
- Carlos Zozaya-Gorostiza 

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
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: International Journal on Interactive Design and Manufacturing
publication_short: IJIDeM

abstract: 
  In a globalized world, the need to speak foreign languages, particularly English, is imperative. One challenge for learning foreign languages at the scale of millions is that, although teaching content is widely available, speaking skills are harder to develop than vocabulary, because feedback from a teacher is needed to correct pronunciation, intonation, etc. There are currently no automated tools to evaluate the fluency or pronunciation level of language students, so this evaluation, which is required even for placing the student into the right level, requires an interview with a language teacher. We have proposed a supervised machine-learning method for automatically evaluating both the fluency and the pronunciation of a language student, as well as detecting specific pronunciation mistakes, taking English as the target language. In order to train a classifier for the classes “low”, “intermediate” and “high”, we first built datasets of audio samples of English-learning students talking. Each audio was divided into small segments, and for each segment a set of features were calculated. We trained several classifiers, which made predictions about the level of a given non-native English speaker. We performed a series of tests with the trained classifiers, comparing the predicted class of audio segments not included in the training dataset, for accuracy, precision, and other measures. Results were promising, as for both fluency and pronunciation we obtained accuracy values of 94% and 99.9% in predictions, the second one being the highest accuracy ever reported on the literature for such predictions.

# Summary. An optional shortened abstract.
summary: We have proposed a supervised machine-learning method for automatically evaluating both the fluency and the pronunciation of a language student, as well as detecting specific pronunciation mistakes, taking English as the target language.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/content/pdf/10.1007/s12008-021-00759-z.pdf'
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
