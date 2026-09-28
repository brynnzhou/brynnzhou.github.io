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

        My current work investigates audio-visual interactions, soundscapes, natural sounds, and greenery, with broader interests in environmental restorativeness, human health and well-being, and design visualization and auralization.
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
