
---
title: 'Clinically Grounded Privacy Evaluation of Medical LMs'

authors:
  - Sasha Ronaghi
  - Sana Tonekaboni
  - admin
  - Vivian Utti
  - Jordan Li Cahoon
  - Nathaniel Hendrix
  -  Ayin Vala
  -  Marzyeh Ghassemi
  -  Emily Alsentzer

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: 2026-09-09
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: 2026-09-09

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *EMNLP 2026*
publication_short: ''

abstract: | 
  Medical language models (LMs) can memorize and reproduce protected health information, but privacy evaluations often focus on recovery of training text rather than disclosure under realistic threat models. We introduce a clinically grounded framework that evaluates leakage along a graded axis of adversarial access, ranging from publicly inferable demographics to leaked note fragments. At each tier, we measure verbatim memorization of patient-specific text and semantic leakage of sensitive diagnoses. Applying the framework to an LM continually pretrained on 378k clinical notes, we find that routine encounter metadata (i.e., name, date of birth, visit date, provider name, and practice location) elicits high rates of verbatim memorization across a patient's timeline and sensitive-diagnosis recovery (AUROC 0.91 for abortion, 0.82 for HIV). At the same time, exact-match memorization can overstate disclosure: 36\% of memorized tokens reflect templated documentation. Our work highlights the risks of training on longitudinal clinical data and provides a practical, reusable framework for contextual privacy evaluation of medical LMs.

# Summary. An optional shortened abstract.
summary: | 
  Medical language models can leak sensitive patient information, but standard memorization metrics may not reflect realistic privacy risks. We introduce a clinically grounded framework that evaluates leakage across levels of adversarial access, revealing substantial patient-specific and sensitive-diagnosis leakage while showing that exact-match memorization can overstate disclosure due to templated clinical text.

#tags:
#  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org



url_pdf: 'https://arxiv.org/pdf/2606.09590'
url_code: 'https://github.com/alsentzerlab/clinical_privacy_eval'
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
