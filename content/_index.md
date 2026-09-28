---
# Homepage
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:

  # ─────────────────────────────────────────────
  # PROFILE / ABOUT
  # ─────────────────────────────────────────────
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
      # Clean background rather than the default colorful gradient
      background:
        gradient_mesh:
          enable: false

      # Slightly restrained name size
      name:
        size: md

      # Profile photo
      avatar:
        size: medium
        shape: circle


  # ─────────────────────────────────────────────
  # RESEARCH
  # ─────────────────────────────────────────────
  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research focuses on human–environment interactions, particularly how visual and acoustic characteristics of urban environments influence perceptual, psychological, and physiological responses.

        My current work investigates audio-visual interactions, soundscapes, natural sounds, and greenery, with broader interests in environmental restorativeness, human health and well-being, and design visualization and auralization.

    design:
      columns: '1'


  # ─────────────────────────────────────────────
  # PUBLICATIONS
  # ─────────────────────────────────────────────
  - block: collection
    id: publications
    content:
      title: 'Publications'
      subtitle: ''
      text: ''

      filters:
        folders:
          - publications
        exclude_featured: false

    design:
      view: citation
      columns: 1


  # ─────────────────────────────────────────────
  # PRESENTATIONS
  # ─────────────────────────────────────────────
  - block: collection
    id: presentations
    content:
      title: 'Presentations'
      subtitle: ''
      text: ''

      filters:
        folders:
          - events

    design:
      view: citation
      columns: 1

---
