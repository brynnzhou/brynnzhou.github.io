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
          <div style="font-size: 1.25rem; font-weight: 600; color: #18181B; line-height: 1.35; margin-bottom: 0.3rem;">
            PhD in Architecture
          </div>

          <div style="font-size: 1.08rem; color: #3F3F46; line-height: 1.5; margin-bottom: 0.65rem;">
            National University of Singapore · 2022–2026
          </div>

          <div style="font-size: 1.05rem; color: #52525B; line-height: 1.65; margin-bottom: 0.25rem;">
            Thesis: <em>Effects of Natural Sounds and Greenery on Soundscape Experience: Dose-Response Relationships, Thresholds, and Exposure Characteristics</em>
          </div>

          <div style="font-size: 1.05rem; color: #3F3F46; line-height: 1.65;">
            Advisors: Prof. Tan Puay Yok and Prof. Lau Siu Kit
          </div>
        </div>


        <div style="margin-bottom: 2.2rem;">
          <div style="font-size: 1.25rem; font-weight: 600; color: #18181B; line-height: 1.35; margin-bottom: 0.3rem;">
            Master of Landscape Architecture
          </div>

          <div style="font-size: 1.08rem; color: #3F3F46; line-height: 1.5; margin-bottom: 0.65rem;">
            National University of Singapore · 2019–2021
          </div>

          <div style="font-size: 1.05rem; color: #52525B; line-height: 1.65; margin-bottom: 0.25rem;">
            Dissertation: <em>A Comparison of Photogrammetry Generated Point Clouds and 360 Degree Panoramic Photos for Semi-immersive Online Teaching of Landscape Architecture</em>
          </div>

          <div style="font-size: 1.05rem; color: #3F3F46; line-height: 1.65;">
            Advisor: Dr. Lin Shengwei Ervine
          </div>
        </div>


        <div>
          <div style="font-size: 1.25rem; font-weight: 600; color: #18181B; line-height: 1.35; margin-bottom: 0.3rem;">
            Bachelor of Environmental Design
          </div>

          <div style="font-size: 1.08rem; color: #3F3F46; line-height: 1.5;">
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
          <div style="font-size: 1.25rem; font-weight: 600; color: #18181B; line-height: 1.35; margin-bottom: 0.3rem;">
            Teaching Assistant
          </div>

          <div style="font-size: 1.08rem; color: #3F3F46; line-height: 1.5; margin-bottom: 0.65rem;">
            National University of Singapore · August 2025–December 2025
          </div>

          <div style="font-size: 1.05rem; color: #52525B; line-height: 1.65;">
            LAD1003 Introduction to Landscape Architecture
          </div>
        </div>


        <div>
          <div style="font-size: 1.25rem; font-weight: 600; color: #18181B; line-height: 1.35; margin-bottom: 0.3rem;">
            Teaching Assistant
          </div>

          <div style="font-size: 1.08rem; color: #3F3F46; line-height: 1.5; margin-bottom: 0.65rem;">
            National University of Singapore · October 2024–December 2024
          </div>

          <div style="font-size: 1.05rem; color: #52525B; line-height: 1.65;">
            LA4702 MLA Optional Studio
          </div>
        </div>

    design:
      columns: '1'


  # Publications
  - block: markdown
    id: publications
    content:
      title: 'Publications'
      subtitle: ''
      text: |-
        <div style="margin-bottom: 2.8rem;">

          <div style="width: 100%; height: 300px; box-sizing: border-box; background: rgba(24, 24, 27, 0.05); border: 1px solid rgba(24, 24, 27, 0.08); border-radius: 18px; overflow: hidden; display: flex; justify-content: center; align-items: center; margin-bottom: 1.2rem;">
            <img src="/uploads/jem-2026.jpg" alt="Publication image" style="width: 100%; height: 100%; object-fit: contain; display: block;">
          </div>

          <div style="font-size: 1.05rem; color: #3F3F46; line-height: 1.65;">
            <strong>Zhou, Z.</strong>, Tan, P.Y., Lau, S.K., Zhang, X., Long, S.X., Chen, X., and Song, X.P. (2026).
            “Exploring relationships between qualitative attributes of urban greenery and soundscape quality assessment: A case study in Singapore.”
            <em>Journal of Environmental Management</em>, 410, 130034.
            <br>
            <a href="https://doi.org/10.1016/j.jenvman.2026.130034" target="_blank">https://doi.org/10.1016/j.jenvman.2026.130034</a>
          </div>

        </div>


        <div style="margin-bottom: 2.8rem;">

          <div style="width: 100%; height: 300px; box-sizing: border-box; background: rgba(24, 24, 27, 0.05); border: 1px solid rgba(24, 24, 27, 0.08); border-radius: 18px; overflow: hidden; display: flex; justify-content: center; align-items: center; margin-bottom: 1.2rem;">
            <img src="/uploads/buildenv-2026.jpg" alt="Publication image" style="max-width: 90%; max-height: 90%; width: auto; height: auto; object-fit: contain; display: block;">
          </div>

          <div style="font-size: 1.05rem; color: #3F3F46; line-height: 1.65;">
            Zhang, X., <strong>Zhou, Z.</strong>, Long, S.X., Chen, T., Chen, X., Song, X.P., Chong, K.Y., Lau, S.K., Yuan, C., and Tan, P.Y. (2026).
            “Monitoring neighborhood-scale urban ecosystem services in high-density housing developments using sensor-based multi-source data.”
            <em>Building and Environment</em>, 305, 115276.
            <br>
            <a href="https://doi.org/10.1016/j.buildenv.2026.115276" target="_blank">https://doi.org/10.1016/j.buildenv.2026.115276</a>
          </div>

        </div>


        <div style="font-size: 1.05rem; color: #3F3F46; line-height: 1.65;">
          Zhu, Y., Wang, J., Zhang, Y., Hwang, Y.H., Chi, D., Qiu, Y., Chen, X., Feng, C., <strong>Zhou, Z.</strong>, Huang, J., Burlando, P., and Tan, P.Y.
          “Research-informed tools as a science-practice interface for mediating multifunctional design: reflections from a collaborative design research studio.”
          <em>Socio-Ecological Practice Research</em>, in press.
        </div>

    design:
      columns: '1'


  # Contact
  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        <div style="font-size: 1.05rem; color: #3F3F46; line-height: 1.65;">
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

  /* Subtle translucent section frame */
  border: 1px solid rgba(24, 24, 27, 0.10);
  border-radius: 16px;
  margin-top: 16px;
  margin-bottom: 16px;
  overflow: hidden;
}

/* About biography */
#about .article-style,
#about .bio-text,
#about p {
  font-size: 1.05rem !important;
  line-height: 1.65 !important;
}

/* Keep section headings visually consistent */
#experience h1,
#experience h2,
#teaching h1,
#teaching h2,
#publications h1,
#publications h2,
#contact h1,
#contact h2 {
  line-height: 1.25 !important;
}
</style>
