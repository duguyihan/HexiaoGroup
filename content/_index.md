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
        
        本课题组致力于关注建筑结构的安全。主要有以下两个方向:

        **模块化钢结构**。面对在人口红利逐步消失、 劳动力短缺、人工成本昂贵，传统现场施工方式面临环境污染、建筑垃圾量大、施工噪音等日益突出的困境下，系统研究像汽车一样造房子的建造方式，符合住建部大力推动装配式钢结构住宅的政策趋势。

        **结构抗连续倒塌**。面对现有结构年限久远，容易发生倒塌的情况，成体系研究结构防连续倒塌的设计方法，包括设计性能目标的确定，寻找框架结构薄弱构件，采用非迭代的方法直接设计，以及基于可靠度和风险的设计方法等。
    
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
