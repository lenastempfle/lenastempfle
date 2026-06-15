---
title: ""
date: 2025-01-26
type: landing

design:
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: "center"
          parallax: false

  - block: markdown
    content:
      title: 📚 My Research
      text: |
        At the Healthy ML Lab, we take inspiration from real-world healthcare challenges to develop machine learning models and theory that improve clinical decision-making. Collaborating closely with clinician networks, hospitals, and healthcare providers, we aim to enhance decision-making, improve patient outcomes, and deepen our understanding of complex medical conditions. Our research spans fairness, privacy, interpretability, and human-AI interaction in healthcare, including studying how machine learning systems affect different patient groups, how biases emerge in medical data and models, and how AI can be designed and evaluated to support equitable and trustworthy clinical care.

        I am a postdoctoral researcher at MIT and the Broad Institute, working on reliable and trustworthy AI systems for healthcare and biomedical data. My research focuses on foundation model evaluation, multimodal and longitudinal health data, clinically grounded AI evaluation, and machine learning under missingness. I have worked on wearable foundation models, memorization and privacy risks in foundation models, interpretable machine learning, and large-scale health prediction systems.
                
        Let’s collaborate! 🚀
    design:
      columns: '1'

  - block: markdown
    id: news
    content:
      title: 📣 Recent News
      text: |
        - **[Jun 2026]** I am giving a talk at KTH on Causal AI for Healthcare.
        - **[Mai 2026]** We released a preprint on [Evaluation without Generation: Non-Generative Assessment of Harmful Model Specialization with Applications to CSAM](https://arxiv.org/abs/2604.25119).
        - **[Dec 2025]** I am traveling to NeurIPS in San Diego.
        - **[Sep 2025]** I started my postdoc at MIT.
        - **[Aug 2025]** I graduated from my PhD at Chalmers.
        - **[Jan 2025]** I am giving a talk at the Traumabase Annual Meeting on a user study with the clinician network, exploring interpretable ML for missing values.
        - **[Nov 2024]** My work on [Expert Study on Interpretable Machine Learning Models with Missing Values](https://arxiv.org/abs/2411.09591) has been accepted to ML4H as a workshop paper. I co-authored the paper [Representing Patient History for Interpretable Policy Modeling](https://arxiv.org/abs/2412.07895), also accepted to ML4H 2024.
        - **[Apr 2024]** My paper on [MINTY: Rule-based Models that Minimize the Need for Imputing Features with Missing Values](https://proceedings.mlr.press/v238/stempfle24a/stempfle24a.pdf) has been accepted to AISTATS.
        - **[Jun 2023]** My paper on [Learning Replacement Variables in Interpretable Rule-based Models](https://openreview.net/pdf?id=71osQuRCfi) has been accepted to the 3rd Workshop on Interpretable Machine Learning in Healthcare (IMLH).
        - **[Nov 2022]** My paper on [Sharing Pattern Submodels for Prediction with Missing Values](https://ojs.aaai.org/index.php/AAAI/article/view/26179) has been published in AAAI.
        - **[Feb 2021]** I co-authored the paper on [Predicting Progression & Cognitive Decline in Amyloid-Positive Patients with Alzheimer's Disease](https://alzres.biomedcentral.com/articles/10.1186/s13195-021-00886-5), published in *Alzheimer's Research & Therapy*.
    design:
      columns: '1'
      spacing:
        padding: ['0', '0', '0', '0']

  - block: collection
    id: publications
    content:
      title: 🤖 Recent Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['0', '0', '0', '0']
---

