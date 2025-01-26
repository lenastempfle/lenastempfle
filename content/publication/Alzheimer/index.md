---
title: 'Predicting progression and cognitive decline in amyloid-positive patients with Alzheimer's disease'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hákon Valur Dansson
  - admin
  - Hildur Egilsdóttir
  - Erik Portelius
  - Kaj Blennow 
  - Henrik Zetterberg
  - Fredrik D Johansson
  - Alzheimer’s Disease Neuroimaging Initiative (ADNI)

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-Sep-6'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-Sep-6'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *Alzheimer's Research & Therapy*
publication_short: ''

abstract: Background
In Alzheimer’s disease, amyloid- β (A β) peptides aggregate in the lowering CSF amyloid levels - a key pathological hallmark of the disease. However, lowered CSF amyloid levels may also be present in cognitively unimpaired elderly individuals. Therefore, it is of great value to explain the variance in disease progression among patients with A β pathology.
Methods
A cohort of n=2293 participants, of whom n=749 were A β positive, was selected from the Alzheimer’s Disease Neuroimaging Initiative (ADNI) database to study heterogeneity in disease progression for individuals with A β pathology. The analysis used baseline clinical variables including demographics, genetic markers, and neuropsychological data to predict how the cognitive ability and AD diagnosis of subjects progressed using statistical models and machine learning. Due to the relatively low prevalence of A β pathology, models fit only to A β-positive subjects were compared to models fit to an extended cohort including subjects without established A β pathology, adjusting for covariate differences between the cohorts.
Results
A β pathology status was determined based on the A β42/A β40 ratio. The best predictive model of change in cognitive test scores for A β-positive subjects at the 2-year follow-up achieved an R2 score of 0.388 while the best model predicting adverse changes in diagnosis achieved a weighted F1 score of 0.791. A β-positive subjects declined faster on average than those without A β pathology, but the specific level of CSF A β was not predictive of progression rate. When predicting cognitive score change 4 years after baseline, the best model achieved an R2 score of 0.325 and it was found that fitting models to the extended cohort improved performance. Moreover, using all clinical variables outperformed the best model based only on a suite of cognitive test scores which achieved an R2 score of 0.228.
Conclusion
Our analysis shows that CSF levels of A β are not strong predictors of the rate of cognitive decline in A β-positive subjects when adjusting for other variables. Baseline assessments of cognitive function accounts for the majority of variance explained in the prediction of 2-year decline but is insufficient for achieving optimal results in longer-term predictions. Predicting changes both in cognitive test scores and in diagnosis provides multiple perspectives of the progression of potential AD subjects.


# Summary. An optional shortened abstract.
summary: CSF Aβ levels alone are not strong predictors of cognitive decline in Aβ-positive individuals, but baseline cognitive assessments explain most of the variance in short-term (2-year) predictions. Including additional clinical variables and extending the cohort to Aβ-negative individuals improves model performance, highlighting the complexity of Alzheimer’s disease progression.

#tags:
#  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://alzres.biomedcentral.com/articles/10.1186/s13195-021-00886-5'
url_code: 'https://github.com/Healthy-AI/alzheimers-progression'
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