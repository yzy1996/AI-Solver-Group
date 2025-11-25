---
# Leave the homepage title empty to use the site title
title: 
date: 2025-05-29
type: landing

sections:
  - block: hero
    content:
      title: 
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        专注于算法自动发现和优化，为AI4EDA、求解器、大模型推理加速和行业应用提供核心技术支撑

  - block: markdown
    content:
      title: 
      text: |
        <div style="background:rgba(255,255,255,0.95);border-radius:20px;padding:40px;margin-bottom:30px;box-shadow:0 20px 40px rgba(0,0,0,0.1);">
          <div style="width:200px;height:200px;border-radius:50%;background:linear-gradient(45deg,#ff6b6b,#ee5a52);display:flex;align-items:center;justify-content:center;margin:0 auto 40px;color:white;font-size:1.3em;font-weight:bold;text-align:center;box-shadow:0 10px 30px rgba(238,90,82,0.4);">
            算法发现<br>核心引擎
          </div>
          <div style="display:flex;justify-content:center;gap:20px;margin:40px 0;">
            <span style="font-size:2em;color:#667eea;">↓</span>
          </div>
          <div style="display:grid;grid-template-columns:1fr 1fr;grid-template-rows:1fr 1fr;gap:30px;">
            <div style="background:linear-gradient(135deg,#667eea,#764ba2);border-radius:15px;padding:10px;color:white;text-align:center;grid-column:1;grid-row:1;">
              <h3 style="color:white;">🔬 AI4EDA</h3>
              <p>电子设计自动化领域的AI算法应用，优化芯片设计流程，提升设计效率和质量</p>
            </div>
            <div style="background:linear-gradient(135deg,#667eea,#764ba2);border-radius:15px;padding:10px;color:white;text-align:center;grid-column:2;grid-row:1;">
              <h3 style="color:white;">⚡ AI求解器</h3>
              <p>高性能优化求解器，解决复杂约束优化问题，支持大规模工程计算</p>
            </div>
            <div style="background:linear-gradient(135deg,#667eea,#764ba2);border-radius:15px;padding:10px;color:white;text-align:center;grid-column:1;grid-row:2;">
              <h3 style="color:white;">🚀 大模型推理加速</h3>
              <p>深度学习模型推理优化，提升模型部署效率，降低计算成本</p>
            </div>
            <div style="background:linear-gradient(135deg,#667eea,#764ba2);border-radius:15px;padding:10px;color:white;text-align:center;grid-column:2;grid-row:2;">
              <h3 style="color:white;">🏢 ToB行业应用</h3>
              <p>面向企业的行业解决方案，将核心算法技术转化为商业价值</p>
            </div>
          </div>
        </div>

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
