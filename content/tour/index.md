---
title: Tour
date: 2022-10-24

type: landing

sections:

  #- block: hero
  #  content:
  #    title: |
  #      Yuansilencer
  #    image:
  #      filename: welcome.jpg
  #    text: |
  #      <br>
        
  #      The **Green Molecules Conversion Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  - block: collection
    content:
      title: Research Topics
      subtitle: Our main research directions
      text: Our research covers multiple frontier topics in catalysis, energy, and advanced materials.
      count: 6
      filters:
        folders:
          - research    # 自动抓取 content/research/ 下所有 md 文件
      order: asc
    design:
      view: card
      columns: '1'
  
  #- block: markdown
  #  content:
  #    title: 'Projects'
  #    subtitle: ''
  #    text:
  #  design:
  #    columns: ''
  #    background:
  #      image: 
  #        filename: coders.jpg
  #        filters:
  #          brightness: 1
  #        parallax: false
  #        position: center
  #        size: cover
  #        text_color_light: true
  #    spacing:
  #      padding: ['20px', '0', '20px', '0']
  #    css_class: fullscreen
  
  

  - block: collection
    content:
      title: Projects
      subtitle: Ongoing projects
      text: A showcase of our group's current and previous projects.
      count: 6
      filters:
        folders:
          - project    # 自动抓取 content/project/ 下所有 md 文件
        status: ongoing
      order: desc
    design:
      view: card
      columns: 2
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: " "
      subtitle: "Completed projects"
      count: 50
      filters:
        folders:
          - project
        status: past
      order: desc
    design:
      view: compact
      columns: 1

  - block: markdown
    content:
       title:
       subtitle:
       text: |
         {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
       columns: '1' 
---
