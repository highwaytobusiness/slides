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
   
- title: Where you can travel with us?
   slide-data: A sunny autumn on the coast does not have to be a ten-hour flight away. Nice bathing weather, cozy and affordable hotels, exciting waves and soft bright sandy beaches are closer than you think.
     
 - title: How you get there?
   slide-data: A flight of <strong>less</strong> than 3 hours takes you to Bucharest, where the adventure of hot salty Black Sea begins.
   
 - title: Why should I care?
   slide-data: Experience Transylvania is the personal travel agency that takes you to the heart of Europe's perhaps most mysterious area. With us you get the real Experience!<pre><code>
       
                &nbsp;"Transylvania, best in travel destination 2016"&nbsp; - Lonely Planet
                
                 </code></pre>   
   
 - title: Get travel tips, info & offers 
   slide-data: Visit our <a href="https://transylvania.se">website</a>. And subscribe to our <a href="https://www.instagram.com/xtransylvaniax/">instagram</a> account.
   background: '#e74c3c'
---

{% for slide in page.slides %}                 
<section data-background="{% if slide.image %}{{slide.image}}{% elsif slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
        <h1>{{slide.title}}</h1>{{ slide.slide-data }}

</section>               
{% endfor %}
    
