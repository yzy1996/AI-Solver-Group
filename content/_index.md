---
# Leave the homepage title empty to use the site title
title: 
date: 2025-05-29
type: landing

sections:
  # - block: hero
  #   content:
  #     title: 
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
        
  #       专注于算法自动发现和优化，为AI4EDA、求解器、大模型推理加速和行业应用提供核心技术支撑

  - block: markdown
    id: hero
    content:
      title: "<span style='color: white;'>华为·诺亚方舟实验室·AI应用创新实验室</span>"
      subtitle: "<span style='color: white;'>专注于算法自动发现和优化，为AI4EDA、求解器、大模型推理加速和行业应用提供核心技术支撑</span>"
      text: 
    design:
      background:
        image:
          filename: background.jpg
          filters:
            brightness: 0.8

  - block: features
    content:
      title: "主要研究方向"
      items:
        - name: "大模型推理加速"
          description: "提升模型吞吐和降低部署成本"
          icon: "bolt"
        - name: "自动算法设计"
          description: "结合大型语言模型（LLMs）和进化计算（EC），实现高效的算法自动启发式设计（AHD）"
          icon: "heart"
        - name: "ToB产业赋能"
          description: "为大模型在多个行业应用落地提供核心技术支撑"
          icon: "building"
    design:
      columns: "3"
      background:
        color: "gray-20"

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

  # - block: collection
  #   content:
  #     title: "Recent Posts"
  #     subtitle: "Latest updates from our blog"
  #     text: "Stay up to date with our latest news and insights"
  #     count: 3
  #   design:
  #     view: "card"
  #     columns: "1"




  - block: collection
    content:
      title: Latest Preprints
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
---
