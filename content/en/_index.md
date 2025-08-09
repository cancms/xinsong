---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
#type: landing
type: home_index
#subTitle: Animal Physiological Ecology and Conservation


 
newsBlock:
  block: collection
  content:
    title: News
    count: 10
    
    offset: 0
    order: desc
    page_type: event
    archive: 
      text: View more
  design:
    view: list_news
    columns: '1' 
         
         
collaborators:

  - image: image/collaborator/dx1.png
    title:  

  - image: image/collaborator/dx2.png
    title:  
 



  
heroSlideBlock:
  block: slider
  content:
    slides:
    - title: 
      content: 
      align: center
      background:
        image:
          filename: group_slides/research_topic.jpg
          filters:
            brightness: 1
        position: right
        color: '#666'  
    - title: 
      content: 
      align: left
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 1
        position: right
        color: '#666'  
  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '320px'
    is_fullscreen: false
    # Automatically transition through slides?
    loop: false
    # Duration of transition between slides (in ms)
    interval: 2000

 




---
