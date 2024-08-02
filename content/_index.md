---
# Leave the homepage title empty to use the site title
title:
date: 2024-07-17
type: landing

sections:
  - block: hero
    id: welcome
    content:
      title: Interactive Intelligent Systems Group
      image:
        filename: welcome.jpg
      text: >-
        <br>
        Our research is dedicated to interactive intelligent systems. We investigate intelligent technologies, study the needs and implications of human interaction with these systems, and their societal implications.<br><br>
  
  - block: collection
    id: news
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - news
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
    design:
      view: compact
      columns: '2'

  - block: slider
    id: tour
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we are working on...
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#FFFFFF'
        link:
          icon: eye
          icon_pack: fas
          text: Take a tour
          url: "#tour"
      - title: We are part of EXDIGIT
        content: >-
          We are part of Excellence in Digital Sciences and Interdisciplinary Technologies (EXDIGIT) at the [Faculty of Digital and Analytical Sciences](https://www.plus.ac.at/digital-and-analytical-sciences/?lang=en) at the [Department of Artificial Intelligence and Human Interfaces (AIHI)](https://www.plus.ac.at/aihi/?lang=en) at the [Paris Lodron University Salzburg](https://plus.ac.at?lang=en), Austria.
          <br><br>
          EXDIGIT aims to strengthen interdisciplinary research skills in the field of digital sciences and interdisciplinary technologies in Salzburg.
        align: left
        background:
          image:
            filename: albums/20240604_dasistexdigit/exdigitgroup_fun_innovation_salzburg_benedikt_schemmer.jpg
            filters:
              brightness: 0.9
          position: Smart
          color: '#FFFFFF'
      - title: Bachelor and master thesis projects
        content: ''
        align: right
        background:
          image:
            filename: computer.jpg
            caption: 'Image by [**Sebastian**](https://pixabay.com/de/users/sebagee-154213/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=423588) from [**Pixabay**](https://pixabay.com/de//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=423588).'
            filters:
              brightness: 0.6
          position: center
          color: '#FFFFFF'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Interested in a thesis project?
          url: ../thesis-projects/
      - title: We like coffee ☕️
        content: "Let's talk about research over a coffee and explore exciting new topics together!"
        align: left
        background:
          image:
            filename: coffee.jpg
            filters:
              brightness: 0.8
          position: center
          color: '#FFFFFF'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000
  - block: collection
    id: latestpublications
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publications
        #publication_type: 'article'
    design:
      view: citation
      columns: '2'

  - block: hero
    id: meettheteam
    content:
      title: Meet the team
      image:
        filename: welcome.jpg
      cta:
        label: Meet the team →
        url: ./team/
        icon_pack: fas
        icon: people-group
      text: >-
        Our research activities center on interactive intelligent systems, integrating research on intelligent technologies, the interaction of humans with intelligent systems, and heir interplay. 
        <br><br>

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: >-
        We are part of Excellence in Digital Sciences and Interdisciplinary Technologies (EXDIGIT) at the [Faculty of Digital and Analytical Sciences](https://www.plus.ac.at/digital-and-analytical-sciences/?lang=en) at the [Department of Artificial Intelligence and Human Interfaces (AIHI)](https://www.plus.ac.at/aihi/?lang=en) at the [Paris Lodron University Salzburg](https://plus.ac.at?lang=en), Austria.

      email: pmo.exdigit@plus.ac.at
      phone: +43 662 8044 – 6370
      address:
        street: Jakob-Haringer-Strasse 1 | Techno 1 | EXDIGIT
        city: Salzburg
        postcode: '5020'
        country: Austria
        country_code: AT
      directions: Enter Techno 1 and take the stairs to EXDIGIT on Floor 3
      office_hours:
        - 'Monday--Thursday 10:00 to 16:00'
      # Automatically link email and phone or display them just as text?
      autolink: false
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '47.82243172623602'
        longitude: '13.040599452092538'
    design:
      columns: '2'
---
