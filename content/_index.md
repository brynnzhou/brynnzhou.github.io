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
        <div style="margin-bottom: 2.2rem;">
          <div style="font-size: 1.20rem; font-weight: 650; color: #F1F1F3; margin-bottom: 0.3rem;">
            PhD in Architecture
          </div>

          <div style="font-size: 1rem; color: #B8BCC6; margin-bottom: 0.65rem;">
            National University of Singapore · 2022–2026
          </div>

          <div style="font-size: 0.92rem; color: #9297A3; line-height: 1.6; margin-bottom: 0.25rem;">
            Thesis: <em>Effects of Natural Sounds and Greenery on Soundscape Experience: Dose-Response Relationships, Thresholds, and Exposure Characteristics</em>
          </div>

          <div style="font-size: 0.92rem; color: #AEB3BD;">
            Advisors: Prof. Tan Puay Yok and Prof. Lau Siu Kit
          </div>
        </div>


        <div style="margin-bottom: 2.2rem;">
          <div style="font-size: 1.20rem; font-weight: 650; color: #F1F1F3; margin-bottom: 0.3rem;">
            Master of Landscape Architecture
          </div>

          <div style="font-size: 1rem; color: #B8BCC6; margin-bottom: 0.65rem;">
            National University of Singapore · 2019–2021
          </div>

          <div style="font-size: 0.92rem; color: #9297A3; line-height: 1.6; margin-bottom: 0.25rem;">
            Dissertation: <em>A Comparison of Photogrammetry Generated Point Clouds and 360 Degree Panoramic Photos for Semi-immersive Online Teaching of Landscape Architecture</em>
          </div>

          <div style="font-size: 0.92rem; color: #AEB3BD;">
            Advisor: Dr. Lin Shengwei Ervine
          </div>
        </div>


        <div>
          <div style="font-size: 1.20rem; font-weight: 650; color: #F1F1F3; margin-bottom: 0.3rem;">
            Bachelor of Environmental Design
          </div>

          <div style="font-size: 1rem; color: #B8BCC6;">
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
