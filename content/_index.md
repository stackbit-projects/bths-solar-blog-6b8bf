---
title: Home
hide_title: true
sections:
  - type: section_hero
    template: section_hero
    title: Welcome to the BTHS Solar Blog
    section_id: hero
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
    actions:
      - type: action
        template: action
        label: Visit our Homepage
        style: button
        url: 'https://bthssolar.org/'
  - type: section_portfolio
    template: section_portfolio
    title: Recent Work
    section_id: latest-projects
    subtitle: An optional subtitle of the section
    layout_style: mosaic
    projects_number: 6
    view_all_label: View All
    view_all_url: portfolio
  - type: section_posts
    template: section_posts
    title: Latest from the Blog
    section_id: latest-posts
    subtitle: An optional subtitle of the section
    posts_number: 3
    col_number: three
    actions:
      - type: action
        template: action
        label: View Blog
        url: blog
        style: button
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: BTHS Solar | Blog
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Exto Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Exto theme
      keyName: property
    - name: 'og:image'
      value: images/exto_preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Exto Theme
    - name: 'twitter:description'
      value: The preview of the Exto theme
    - name: 'twitter:image'
      value: images/exto_preview.png
      relativeUrl: true
  description: >-
    The Brooklyn Technical High School Solar Car Team Blog. Team updates,
    highlights, and more.
layout: advanced
---
