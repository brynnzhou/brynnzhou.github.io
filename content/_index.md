---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:

  # About
  - block: resume-biography
    id: about
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


  # Experience
  - block: markdown
    id: experience
    content:
      title: 'Experience'
      subtitle: ''
      text: |-
        <div style="margin-bottom: 2.2rem;">
          <div style="font-size: 1.20rem; font-weight: 650; color: #18181B; margin-bottom: 0.3rem;">
            PhD in Architecture
          </div>

          <div style="font-size: 1rem; color: #3F3F46; margin-bottom: 0.65rem;">
            National University of Singapore · 2022–2026
          </div>

          <div style="font-size: 0.92rem; color: #52525B; line-height: 1.6; margin-bottom: 0.25rem;">
            Thesis: <em>Effects of Natural Sounds and Greenery on Soundscape Experience: Dose-Response Relationships, Thresholds, and Exposure Characteristics</em>
          </div>

          <div style="font-size: 0.92rem; color: #3F3F46;">
            Advisors: Prof. Tan Puay Yok and Prof. Lau Siu Kit
          </div>
        </div>


        <div style="margin-bottom: 2.2rem;">
          <div style="font-size: 1.20rem; font-weight: 650; color: #18181B; margin-bottom: 0.3rem;">
            Master of Landscape Architecture
          </div>

          <div style="font-size: 1rem; color: #3F3F46; margin-bottom: 0.65rem;">
            National University of Singapore · 2019–2021
          </div>

          <div style="font-size: 0.92rem; color: #52525B; line-height: 1.6; margin-bottom: 0.25rem;">
            Dissertation: <em>A Comparison of Photogrammetry Generated Point Clouds and 360 Degree Panoramic Photos for Semi-immersive Online Teaching of Landscape Architecture</em>
          </div>

          <div style="font-size: 0.92rem; color: #3F3F46;">
            Advisor: Dr. Lin Shengwei Ervine
          </div>
        </div>


        <div>
          <div style="font-size: 1.20rem; font-weight: 650; color: #18181B; margin-bottom: 0.3rem;">
            Bachelor of Environmental Design
          </div>

          <div style="font-size: 1rem; color: #3F3F46;">
            Tianjin Academy of Fine Arts · 2015–2019
          </div>
        </div>

    design:
      columns: '1'


  # Teaching
  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      subtitle: ''
      text: |-
        <div style="margin-bottom: 2.2rem;">
          <div style="font-size: 1.20rem; font-weight: 650; color: #18181B; margin-bottom: 0.3rem;">
            Teaching Assistant
          </div>

          <div style="font-size: 1rem; color: #3F3F46; margin-bottom: 0.65rem;">
            National University of Singapore · August 2025–December 2025
          </div>

          <div style="font-size: 0.92rem; color: #52525B; line-height: 1.6;">
            LAD1003 Introduction to Landscape Architecture
          </div>
        </div>


        <div>
          <div style="font-size: 1.20rem; font-weight: 650; color: #18181B; margin-bottom: 0.3rem;">
            Teaching Assistant
          </div>

          <div style="font-size: 1rem; color: #3F3F46; margin-bottom: 0.65rem;">
            National University of Singapore · October 2024–December 2024
          </div>

          <div style="font-size: 0.92rem; color: #52525B; line-height: 1.6;">
            LA4702 MLA Optional Studio
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


  # Contact
  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        <div style="font-size: 1rem; color: #3F3F46; line-height: 1.8;">
          <strong>Email:</strong> zuyuan.zhou@u.nus.edu<br>
          <strong>Phone:</strong> +65 9082 7564
        </div>

    design:
      columns: '1'

---

<style>
html {
  scroll-behavior: smooth !important;
}

#about,
#experience,
#teaching,
#publications,
#contact {
  scroll-margin-top: 80px;
}
</style>
