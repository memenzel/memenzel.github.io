---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"
  design:
      css_class: dark, gem

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""

  - block: collection
    id: publications
    content:
      title: Refereed Publications
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: citation

  - block: collection
    id: presentations
    content:
      title: Selected Presentations
      filters:
        folders:
          - presentations
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]

  - block: resume-experience
    id: experience
    content: 
      username: admin
    design:
      title: Teaching
      # Hugo date format 
      date_format: 'January 2006'
      # Education or Experience section first? 
      is_education_first: false 
---
