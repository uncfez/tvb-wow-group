---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  
  - block: hero
    content:
      title: 
      image:
        filename: cropped-icon.png
      cta:
        label: '**Bli medlem**'
        url: https://wowchemy.com/templates/
      cta_alt:
        label: Vad är turf?
        url: https://discord.gg/z8wNYzb

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
      view: showcase
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
          filename: welcome.jpg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  

---