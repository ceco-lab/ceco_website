---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <span style="color:white; font-size: 46px;">Computational ecology<br><span style="color:aliceblue; font-size: 16px;font-style: italic;">Research Group</span></span>

        
      image:
        filename: #welcome.jpg
      text: |
        <br>
        <br>
        <br>
        <p><span style="color:white; font-size: 19 px;">Plant ecology,Computational biology, Metbololomic,conservation... </span>.</p>
     

    design:
        columns: '1'
        background:
          image: 
           filename: entete_group4.jpg
           filters:
             brightness: 1
          parallax: false
          position: center
          size: cover

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
      background:
        color: black
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: entete_group4.jpg
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