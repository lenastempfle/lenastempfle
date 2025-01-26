---
title: "Learning replacement variables in interpretable rule-based models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Fredrik D. Johansson

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-06-20'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-20'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *3rd Workshop on Interpretable Machine Learning in Healthcare (IMLH)*
publication_short: ''

abstract: | 
    Rule models are favored in many prediction tasks due to their interpretation using natural language and their simple presentation. When learned from data, they can provide high predictive performance, on par with more complex models. However, in the presence of incomplete input data during test time, standard rule models’ predictions are undefined or ambiguous. In this work, we consider learning compact yet accurate rule models with missing values at both training and test time, based on the notion of replacement variables. We propose a method called MINTY which learns rules in the form of disjunctions between variables that act as replacements for each other when one or more is missing. This results in a sparse linear rule model that naturally allows a trade-off between interpretability and goodness of fit while being sensitive to missing values at test time. We demonstrate the concept of MINTY in preliminary experiments and compare the predictive performance to baselines with potential applications in clinical scoring systems.

# Summary. An optional shortened abstract.
summary: | 
    MINTY is a method for learning compact and interpretable rule models that handle missing values at both training and test time by using replacement variables, enabling robust predictions and balancing interpretability with predictive performance, particularly in clinical applications.

#tags:
#  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=71osQuRCfi'
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
  caption: 'Figure by Lena Stempfle'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---