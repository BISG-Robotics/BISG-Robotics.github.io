---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
view: compact

sections:
  - block: 
    content:
      title: 
      text:
        <br>
        BISG-Robotics is a multidisciplinary team developing intelligent, autonomous, human-centered robots for real-world challenges, with a strong Arctic focus. We combine perception, machine learning, decision-making, human-robot interaction, and embedded systems for safe, reliable operation even in challenging arctic conditions.

        Our research centres on four areas.

        1. multimodal perception and scene understanding</br>
        2. robot learning and autonomous decision-making,</br>
        3. human-aware interaction and</br>
        4. safety, and resource-efficient embedded computing.</br>

        We fuse data from cameras, LiDAR, radar, and ground-penetrating radar for robust perception in poor visibility and changing conditions, and design architectures that run reliably on power-limited platforms.

        Application areas include industrial automation, logistics, field and outdoor robotics, environmental and forest surveying, and health technology. Our Arctic focus adds emphasis on snow-covered terrain, subsurface sensing, and infrastructure monitoring. We develop impactful sensor technologies and AI-driven autonomy to strengthen industrial competitiveness and support a sustainable, inclusive future.
      design:
        view: card
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
      columns: '2'
  
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
