---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-01-26
type: landing

design:
  # Default section spacing
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        At the Healthy AI Lab, we draw motivation and inspiration from challenges in healthcare settings, developing machine learning models and theory to address real-world clinical needs. Through collaborations with clinician networks, hospitals, and healthcare providers, we strive to create solutions that enhance decision-making, improve patient outcomes, and advance the understanding of complex medical conditions.

        I am a Ph.D. student in the Data Science and AI division at Chalmers University of Technology, working at the intersection of machine learning and healthcare. My research focuses on predictive modeling with missing values, time series forecasting, and developing interpretable and reliable models to support clinical decision-making.
                
        Please reach out to collaborate! 🚀
    design:
      columns: '1'
  - block: markdown
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: |
        - **[Jan 2025]** I am giving a talk at the Traumabase Annual Meeting on a user study with the clinician network, exploring interpretable ML for missing values.
        - **[Nov 2024]** My work on [Expert Study on Interpretable Machine learning models with missing values](https://arxiv.org/abs/2411.09591) has been accepted to ML4H as a workshop paper. I co-authored the work on [representing patient history for interpretable policy modeling](https://arxiv.org/abs/2412.07895) has been accepted to ML4H 2024. 
        - **[Nov 2024]** I co-authored the work on [representing patient history for interpretable policy modeling](https://arxiv.org/abs/2412.07895) has been accepted to ML4H 2024.
        - **[Apr 2024]** My paper on [MINTY: Rule-based Models that Minimize the Need for Imputing
        Features with Missing Values](https://proceedings.mlr.press/v238/stempfle24a/stempfle24a.pdf) has been accepted to AISTATS.
        - **[Jun 2023]** My paper on [Learning Replacement Variables in interpretable rule-based Models](https://openreview.net/pdf?id=71osQuRCfi) has been accepted to 3rd Workshop on Interpretable Machine Learning in Healthcare (IMLH).
        - **[Nov 2022]** My paper on [Sharing pattern submodels for prediction with missing values](https://ojs.aaai.org/index.php/AAAI/article/view/26179) has been published in AAAI.
        - **[Feb 2021]** I co-authored the work on [Predicting progression & cognitive decline in amyloid-positive patients with Alzheimer's disease](https://alzres.biomedcentral.com/articles/10.1186/s13195-021-00886-5) that has been publish in Alzheimer's Research & Therapy
    design:
      columns: '1'
      spacing:
        padding: ['5', '0', '5', '0']
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['0', '0', '0', '0']
  #- block: collection
   # id: talks
    #content:
     # title: Recent & Upcoming Talks
      #filters:
       # folders:
        #  - event
    #design:
     # view: article-grid
     # columns: 1
---