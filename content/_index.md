---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      #button:
       # text: Download CV
       # url: uploads/resume.pdf
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

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        author: "Ye Jia"
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [1, 0, 0, 0]

 
  - block: collection
    content:
      title: Upcoming Publications
      text: ""
      filters:
        folders:
          - upcoming
        exclude_featured: false
        count: 10
    design:
      view: citation

  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

#- block: cta-card
 # demo: false # Only display this section in the Hugo Blox Builder demo site
 # content:
  #  title: 👉 Build your own academic website like this
 #   text: |-
      
 #     From landing pages, second brains, and courses to academic resumés, conferences, and tech #blogs.
#  button:
 #     text: Get Started
 #      url: https://hugoblox.com/templates/
#  design:
  #    card:
   #     # Card background color (CSS class)
   #     css_class: "bg-primary-700"
    #    css_style: ""
---
