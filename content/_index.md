---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-08-16
type: landing

sections:
  - block: resume-biography-3
    content:
      # Empty username uses the main author profile
      username: ''
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Contact Me
        url: 'mailto:sadeghij@brandonu.ca'
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Gradient mesh background
      background:
        gradient_mesh:
          enable: true

      name:
        size: md

      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🔬 Research Focus'
      subtitle: 'Microbial Adaptation & Evolution (MAE) Group'
      text: |-
        Our research investigates the ecological and evolutionary mechanisms shaping microbial communities in natural and managed ecosystems. 

        Using a combination of **multi-omics**, **evolutionary genomics**, and **plant-microbiome experiments**, we explore how environmental stresses and host interactions drive microbial adaptation under climate change.

        Interested in graduate or undergraduate research opportunities? Please reach out to collaborate!
    design:
      columns: '1'

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

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent News & Updates
      subtitle: ''
      text: ''
      page_type: blog
      count: 5
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---