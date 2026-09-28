---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:

  # Biography + Research Interests + Education
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: 'Education'
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: false

      name:
        size: md

      avatar:
        size: medium
        shape: circle


  # Research
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research focuses on human–environment interactions, particularly how visual and acoustic characteristics of urban environments influence perceptual, psychological, and physiological responses.

        I am particularly interested in audio-visual interactions, soundscapes, natural sounds, and greenery, as well as their implications for environmental restorativeness, human health, and well-being.

        My broader research interests include design visualization and auralization, environmental perception, and evidence-based approaches to designing healthier and more restorative urban environments.
    design:
      columns: '1'


  # Featured Publications
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2


  # Publications
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

---
