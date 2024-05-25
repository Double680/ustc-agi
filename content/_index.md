---
# Leave the homepage title empty to use the site title
title: USTC AGI Research Group
type: landing

sections:
  - block: hero
    content:
      title: |
        USTC AGI Group
      text: |
        <br>
        
        **A**rtificial **G**eneral **I**ntelligence group is a part of State Key Laboratory of Cognitive Intelligence, University of Science and Technology of China. AGI group mainly focuses on applying AI & data mining techniques to general applications.
      image:
        filename: welcome.png

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team" %}}
  #   design:
  #     columns: '1'
  - block: collection
    content:
      title: Research
      subtitle:
      text:
      count: 6
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: research
    design:
      view: showcase
      columns: '1'
  - block: collection
    content:
      title: Projects
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: project
    design:
      view: showcase
      columns: '1'
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

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
---