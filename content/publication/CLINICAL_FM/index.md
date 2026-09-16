---
title: "An Investigation of Memorization Risk in Healthcare Foundation Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - "Sana Tonekaboni"
  - admin
  - Adibvafa Fallahpour
  - Walter Gerych
  - Marzyeh Ghassemi

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: 2021-09-06 
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: 2021-09-06

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Advances in Neural Information Processing Systems 38*
publication_short: ''

abstract: |
    Foundation models trained on large-scale de-identified electronic health records
(EHRs) hold promise for clinical applications. However, their capacity to memorize
patient information raises important privacy concerns. In this work, we introduce
a suite of black-box evaluation tests to assess privacy-related memorization risks
in foundation models trained on structured EHR data. Our framework includes
methods for probing memorization at both the embedding and generative levels,
and aims to distinguish between model generalization and harmful memorization in
clinically relevant settings. We contextualize memorization in terms of its potential
to compromise patient privacy, particularly for vulnerable subgroups. We validate
our approach on a publicly available EHR foundation model and release an open-
source toolkit to facilitate reproducible and collaborative privacy assessments in
healthcare AI.


# Summary. An optional shortened abstract.
summary: | 

#tags:
#  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.proceedings.com/content/085/085713-0353open.pdf'
url_code: 'https://github.com/lenastempfle/EHR-FM_memorization'
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
