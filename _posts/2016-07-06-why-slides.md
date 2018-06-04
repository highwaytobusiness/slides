---
title: Experience Transylvania. Why?
layout: post
permalink: /why/
---


<section>
 <h1> What is Experience Transylvania? <h1>
 <h3> Experience Transylvania is the personal travel agency that takes you to the heart of Europe's perhaps most mysterious area. We create group trips and tailor made trips to Transylvania. </h3>
</section>   
    

<section>
 <h1> Another reason to travel with us </h1>
 <h3> We love Transylvania but most of all, we love our customers. We want to create amazing experiences for each of you who want to travel with us. A taste of our travels comes with this film. Feel free to take a trip to see that the reality is even nicer than the pictures! </h3>
   background: '#05a'
</section> 

<section>
 <h1> Where you can travel with us? <h1>
 <h3> A sunny autumn on the coast does not have to be a ten-hour flight away. Nice bathing weather, cozy and affordable hotels, exciting waves and soft bright sandy beaches are closer than you think.
  </h3>
 image: '/slides/images/ro.jpg'
</section>   
 
<section>
 <h1> How you get there? <h1>
 <h3> A flight of <strong>less</strong> than 3 hours takes you to Bucharest, where the adventure of hot salty Black Sea begins. <h3>
   image: '/slides/images/bucharest.jpg'
</section>

<section>
 <h1> Why should I care? <h1>
 <h3> Experience Transylvania is the personal travel agency that takes you to the heart of Europe's perhaps most mysterious area. With us you get the real Experience! <h3><pre><code>
       
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
 <h1> Get travel tips, info & offers <h1>
 <h3> Follow us: <h3>
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
    
