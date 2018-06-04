---
title: Experience Transylvania. Why?
layout: post
permalink: /why/
background: '#0a5'


 <section>
 - title: What is Experience Transylvania?
   slide-data: Experience Transylvania is the personal travel agency that takes you to the heart of Europe's perhaps most mysterious area. We create group trips and tailor made trips to Transylvania.
 </section>   
    

 <section>
 - title: Another reason to travel with us    
   slide-data: We love Transylvania but most of all, we love our customers. We want to create amazing experiences for each of you who want to travel with us. A taste of our travels comes with this film. Feel free to take a trip to see that the reality is even nicer than the pictures!
   background: '#05a'
 </section> 

 <section>
 - title: Where you can travel with us?
   slide-data: A sunny autumn on the coast does not have to be a ten-hour flight away. Nice bathing weather, cozy and affordable hotels, exciting waves and soft bright sandy beaches are closer than you think.
   image: '/slides/images/ro.jpg'
 </section>   
 
 <section>
 - title: How you get there?
   slide-data: A flight of <strong>less</strong> than 3 hours takes you to Bucharest, where the adventure of hot salty Black Sea begins.
   image: '/slides/images/bucharest.jpg'
 </section>
   
   

 <section>
 - title: Why should I care?
   slide-data: Experience Transylvania is the personal travel agency that takes you to the heart of Europe's perhaps most mysterious area. With us you get the real Experience!<pre><code>
       
                &nbsp;"Transylvania, best in travel destination 2016"&nbsp; - Lonely Planet
                
                 </code></pre>   
 </section>
 
 <section>
    <section>
        <h2>See more pictures</h2>
        <p>And don't forget to subscribe to our instagram:</p>
     <p><a href="https://www.instagram.com/xtransylvaniax/">@xtransylvaniax</a></p>
        <br>
        <a href="#" class="navigate-down">
            <img width="78" data-src="https://s3.amazonaws.com/hakim-static/reveal-js/arrow.png" alt="Down arrow">
        </a>
    </section>
    <section>
        <h2>Bucegi, Romania</h2>
    image: '/slides/images/bucegicouple.jpg'     
    </section>
    <section>
        <h2>Sfinx, Bucegi</h2>
        <pThe Sphinx is a natural rock formation in the Bucegi Natural Park which is in the Bucegi Mountains of Romania..</p>
        <br>
     image: '/slides/images/sfinx.jpg' 
        <a href="#/2">
            <img width="78" data-src="https://s3.amazonaws.com/hakim-static/reveal-js/arrow.png" alt="Up arrow" style="transform: rotate(180deg); -webkit-transform: rotate(180deg);">
        </a>
    </section>
 </section>

 
 <section> 
 - title: Get travel tips, info & offers 
   slide-data: Follow us:
   <p>
        <small>Visit our <a href=""https://transylvania.se">Website</a> / and <a href="https://www.instagram.com/xtransylvaniax/">instagram</a></small>
    </p>
   background: '#e74c3c'
 </section>  
---

{% for slide in page.slides %}                 
<section data-background="{% if slide.image %}{{slide.image}}{% elsif slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
        <h1>{{slide.title}}</h1>{{ slide.slide-data }}

</section>               
{% endfor %}
    
