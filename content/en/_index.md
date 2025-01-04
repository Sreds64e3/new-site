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
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        # Uncomment the following lines if you want a background image
        # image:
        #   # Add your image background to `assets/media/`.
        #   filename: stacked-peaks.svg
        #   filters:
        #     brightness: 1.0
        #   size: cover
        #   position: center
        #   parallax: false

  - block: markdown
    content:
      title: "Scientific career | Academic background"
      subtitle: ""
      text: |-
        #### 05/2023 – laufend
        Wissenschaftlicher Mitarbeiter des Projekts “MemorAI Styria” für das Institut für Ethik und Gesellschaftslehre an der Universität Graz

        #### 12/2023 – laufend
        Universitätsassistent am Fachbereich Sozialethik an der Universität Wien

        #### 09/2023 – 04/2024
        Wissenschaftlicher Mitarbeiter der EU-Studie “The protection of mental privacy in the area of neuroscience - societal, legal and ethical challenges” für das Institut für Ethik und Gesellschaftslehre an der Universität Graz

        #### 07/2023 – 04/2024
        Projektmitarbeiter an der Professur für Health Care Ethics an der Universität Graz

        #### 11/2022 – 04/2023
        Universitätsassistent am Institut für Ethik und Gesellschaftslehre an der Universität Graz

        #### 2022
        Diplomstudium der Katholischen Fachtheologie an der Katholisch-Theologischen Fakultät der Universität Graz Sponsion zum Mag.theol mit ausgezeichnetem Erfolg
    design:
      columns: "1"

  - block: markdown
    content:
      title: "Timeline"
      subtitle: ""
      text: |-
        ## January 2018
        **What is Lorem Ipsum?**  
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.

        ---

        ## February 2018
        **What is Lorem Ipsum?**  
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.

        ---

        ## March 2018
        **What is Lorem Ipsum?**  
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.

        ---

        ## April 2018
        **What is Lorem Ipsum?**  
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.

        ---

        ## May 2018
        **What is Lorem Ipsum?**  
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.

    design:
      columns: "1"

  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
#
 # - block: collection
  #  id: talks
   # content:
    #  title: Recent & Upcoming Talks
     # filters:
      #  folders:
       #   - event
    #design:
     # view: article-grid
     # columns: 1

  - block: collection
    id: blog
    content:
      title: Recent post
      subtitle: ""
      text: ""
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
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
        padding: [0, 0, 0, 0]

  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
