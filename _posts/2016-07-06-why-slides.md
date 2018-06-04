---
title: Experience Transylvania. Why?
layout: post
permalink: /why/
background: '#0a5'

slides:
 - title: What is Experience Transylvania?
   slide-data: Experience Transylvania is the personal travel agency that takes you to the heart of Europe's perhaps most mysterious area. We create group trips and tailor made trips to Transylvania.
   background: "#e74c3c"
    
 - title: Another reason to travel with us    
   slide-data: We love Transylvania but most of all, we love our customers. We want to create amazing experiences for each of you who want to travel with us. A taste of our travels comes with this film. Feel free to take a trip to see that the reality is even nicer than the pictures!
   background: '#f1c40f'
   
 - title: Where you can travel with us?
   slide-data: A sunny autumn on the coast does not have to be a ten-hour flight away. Nice bathing weather, cozy and affordable hotels, exciting waves and soft bright sandy beaches are closer than you think.
   image: '/slides/images/ro.jpg'
     
 - title: How you get there?
   slide-data: A flight of <strong>less</strong> than 3 hours takes you to Bucharest, where the adventure of hot salty Black Sea begins.
   image: '/slides/images/bucharest.jpg'   
   
 - title: Why should I care?
   slide-data: Experience Transylvania is the personal travel agency that takes you to the heart of Europe's perhaps most mysterious area. With us you get the real Experience!<pre><code>
       
                &nbsp;"Transylvania, best in travel destination 2016"&nbsp; - Lonely Planet
                
                 </code></pre>   
   
 - title: Adventure at Dracula
  slide-data: A trip to Transylvania often begins with curiosity for the myth behind Dracula.
  image: '/slides/images/dracula.jpg'   
   
  - title: Our selection
  slide-data: Browse our popular travel and call us for tips and advice!
  image: '/slides/images/erbjudanden_transylvanien.jpg' 
   
  - title: Customers are telling
  slide-data: "The trip to Transylvania is one of the best round trips I've been to throughout my life." Thus, Auli, an active and resvan stockholmer, traveled to Transylvania in 2013.
  image: '/slides/images/resa_transylvanien.jpg'
   
  - title: Get travel tips, info & offers 
  slide-data: Visit our <a href="https://transylvania.se">website</a>. And subscribe to our <a href="https://www.instagram.com/xtransylvaniax/">instagram</a> account.
  background: '#1abc9c'
   
  - title: We will help you with the trip
  slide-data: Don't forget to follow us on instagram.
  image: '/slides/images/bucharest.jpg'   

  - title: Get travel tips, info & offers 
  slide-data: Experience Transylvania is the personal travel agency that takes you to the heart of Europe's perhaps most mysterious area. Transylvania is an exciting, safe and affordable destination.
  background: '#9b59b6' 

---

{% for slide in page.slides %}                 
<section data-background="{% if slide.image %}{{slide.image}}{% elsif slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
        <h1>{{slide.title}}</h1>{{ slide.slide-data }}

</section>               
{% endfor %}
    
