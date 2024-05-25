---
# Leave the homepage title empty to use the site title
title:
date: 2024-05-23
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: USTC AGI Group
          content: "**A**rtificial **G**eneral **I**ntelligence (AGI) group is a part of State Key Laboratory of Cognitive Intelligence, University of Science and Technology of China (USTC), which is established in Sept 2023. AGI group mainly focuses on applying machine learning and data mining techniques to general AI applications, including medical analysis, time-series forecasting, technical document mining and personalized recommendation."
          align: center
          background:
            image:
              filename: welcome.png
              filters:
                brightness: 0.7
            position: right
            color: '#666'
      design:
        slide_height: ''
        is_fullscreen: true
        loop: false

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