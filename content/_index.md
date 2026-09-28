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


  # Education
  - block: markdown
    content:
      title: 'Education'
      subtitle: ''
      text: |-
        **PhD in Architecture**  
        National University of Singapore, 2022–2026

        **Master of Landscape Architecture**  
        National University of Singapore, 2019–2021

        **Bachelor of Environmental Design**  
        Tianjin Academy of Fine Arts, 2015–2019
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
