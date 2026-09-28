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
        <div style="margin-bottom: 2rem;">
          <div style="font-size: 1.25rem; font-weight: 600; margin-bottom: 0.25rem;">
            PhD in Architecture
          </div>
          <div style="font-size: 1rem; opacity: 0.75; margin-bottom: 0.65rem;">
            National University of Singapore · 2022–2026
          </div>
          <div style="font-size: 0.9rem; line-height: 1.6; opacity: 0.85;">
            <em>Thesis: Effects of Natural Sounds and Greenery on Soundscape Experience: Dose-Response Relationships, Thresholds, and Exposure Characteristics</em><br>
            Advisors: Prof. Tan Puay Yok and Prof. Lau Siu Kit
          </div>
        </div>

        <div style="margin-bottom: 2rem;">
          <div style="font-size: 1.25rem; font-weight: 600; margin-bottom: 0.25rem;">
            Master of Landscape Architecture
          </div>
          <div style="font-size: 1rem; opacity: 0.75; margin-bottom: 0.65rem;">
            National University of Singapore · 2019–2021
          </div>
          <div style="font-size: 0.9rem; line-height: 1.6; opacity: 0.85;">
            <em>Dissertation: A Comparison of Photogrammetry Generated Point Clouds and 360 Degree Panoramic Photos for Semi-immersive Online Teaching of Landscape Architecture</em><br>
            Advisor: Dr. Lin Shengwei Ervine
          </div>
        </div>

        <div>
          <div style="font-size: 1.25rem; font-weight: 600; margin-bottom: 0.25rem;">
            Bachelor of Environmental Design
          </div>
          <div style="font-size: 1rem; opacity: 0.75;">
            Tianjin Academy of Fine Arts · 2015–2019
          </div>
        </div>
    design:
      columns: '1'


  # Publications
  - block: collection
    id: publications
    content:
      title: 'Publications'
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

---
