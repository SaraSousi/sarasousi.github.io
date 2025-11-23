---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-11-22
type: landing

design:
  # Default section spacing
  spacing: '5rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I'm a research scientist at Imperial College London. My research interrogates how digital and data-driven technologies can genuinely improve healthcare quality.
        I apply advanced computational methods—ranging from machine learning and clustering, to large-scale clinical datasets, such as CPRD, UK Biobank, WSIC.
        My work spans orthopaedics, public health, women's health, digitla health, and population health, consistently grounding analytics in real-world clinical impact.

        Please reach out to collaborate 😃
    design:
      columns: '2'
      spacing:
        padding: [5, 0, 0, 0]
 # - block: collection
 #   id: papers
 #   content:
 #     title: Featured Publications
 #     filters:
 #       folders:
 #         - publications
 #      featured_only: true
 #   design:
 #     view: article-grid
 #     columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - events
#    design:
#      view: card

---
