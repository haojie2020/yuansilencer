---
# Leave the homepage title empty to use the site title
title: 

date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides: 
      - title: 👋 *Welcome to* **YuanSilencer**

        content:   we focus on the research on Silencer.
        align: center
        background:
          image:
            filename: groupimage.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: 
          icon_pack: fas
          text: Check our work...
          url: ../tour/

      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: enjoy
          icon_pack: fas
          text: latest News
          url: ../post/

      - title:  Silencer
        content: ''
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      #slide_height: ''
      slide_height: '70vh'
      is_fullscreen: false
      #is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000

  - block: hero
    content:
      title: |
        YuanSilencer
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **YuanSilencer** is a...
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  


  - block: collection
    content:
      title: Latest publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['200px', '0', '200px', '0']
      css_class: card     
---