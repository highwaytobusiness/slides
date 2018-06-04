---
title: Experience Transylvania. Why?
layout: post
permalink: /why/
background: '#0a5'

slides:
 - title: What is Experience Transylvania?
   slide-data: Experience Transylvania is the personal travel agency that takes you to the heart of Europe's perhaps most mysterious area. We create group trips and tailor made trips to Transylvania.
   
    
 - title: Another reason to travel with us    
   slide-data: We love Transylvania but most of all, we love our customers. We want to create amazing experiences for each of you who want to travel with us. A taste of our travels comes with this film. Feel free to take a trip to see that the reality is even nicer than the pictures!
   background: '#05a'


 - title: Get travel tips, info & offers 
   slide-data: Visit our <a href="https://transylvania.se">website</a>. And subscribe to our <a href="https://www.instagram.com/xtransylvaniax/">instagram</a> account.
   background: '#e74c3c'
---

{% for slide in page.slides %}                 
<section data-background="{% if slide.image %}{{slide.image}}{% elsif slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
        <h1>{{slide.title}}</h1>{{ slide.slide-data }}

</section>               
{% endfor %}
    
