---
title: "An Investigation of Memorization Risk in Healthcare Foundation Models"

authors:
  - Sana Tonekaboni
  - Lena Stempfle
  - Adibvafa Fallahpour
  - Walter Gerych
  - Marzyeh Ghassemi

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: 2025-12-12 
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: 2026-09-17

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Advances in Neural Information Processing Systems 38*
publication_short: 'NeurIPS'

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

