---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        HEXIAO
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        
     #本课题组致力于关注建筑结构的安全。主要有以下两个方向:**结构抗连续倒塌**。面对现有结构年限久远，容易发生倒塌的情况，成体系研究结构防连续倒塌的设计方法，包括设计性能目标的确定，寻找框架结构薄弱构件，采用非迭代的方法直接设计，以及基于可靠度和风险的设计方法等。
  
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
