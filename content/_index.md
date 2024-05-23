---
# Leave the homepage title empty to use the site title
title:
date: 2024-05-23
type: landing

sections:
  - block: hero
    content:
      title: |
        **A**rtificial **G**eneral **I**ntelligence Research Group
      image:
        filename: welcome.png
      text: |
        <br>
        
        AGI Research Group is a part of the State Key Laboratory of Cognitive Intelligence, University of Science and Technology of China (USTC). Our research group mainly focuses on applying big data and machine learning techniques to general AI applications including clinical analysis, time series forcasting, technical mining and recommender systems. 
  
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
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---