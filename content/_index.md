---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:

  # Biography
  - block: resume-biography
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      avatar:
        size: medium
        shape: circle


  # Research Interests + Education
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <div style="display: grid; grid-template-columns: 1fr 1.5fr; gap: 4rem; align-items: start;">

        <div>

        ## Research Interests

        - Audio-Visual Interactions
        - Soundscape
        - Psychophysiological Responses to Urban Environments
        - Human–Environment Interactions and Well-being

        </div>

        <div>

        ## Education

        🎓 **PhD in Architecture**  
        National University of Singapore  
        2022–2026

        🎓 **Master of Landscape Architecture**  
        National University of Singapore  
        2019–2021

        🎓 **Bachelor of Environmental Design**  
        Tianjin Academy of Fine Arts  
        2015–2019

        </div>

        </div>
    design:
      columns: '1'


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
