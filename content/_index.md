---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am a student reseacher with a general interest in speech analysis. My previous work focuses on tonal langauges, specifically Cantonese. I am interested in the application of statistical and corpus method in the field of speech production and percetion, language and sound variation. 

        I am always open to collaboration. Please reach out! 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Papers and Abstracts
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
