---
title: Maps
layout: post
permalink: /maps/
theme: white
 
slides:
 - title: Romania
   slide-data: Our second route
   image: '/slides/images/romania.png'
 
     
 - title: Transylvania
   slide-data: This is second slide
   image: '/slides/images/transylvania.png'

   
 - title: Banat
   slide-data: This is third slide
   image: '/slides/images/banat.png'
   
      
 - title: Maramures
   slide-data: This is third slide
   image: '/slides/images/maramures.png'
   
      
 - title: Moldova
   slide-data: This is third slide
   image: '/slides/images/moldova.png'
   
      
 - title: Oltenia
   slide-data: This is third slide
   image: '/slides/images/oltenia.png'
    
 - title: Dobrogea
   slide-data: This is third slide
   image: '/slides/images/dobrogea.png'
   
      
 - title: Wallachia
   slide-data: This is third slide
   image: '/slides/images/ro.jpg'
   
      
 - title: Our third route
   slide-data: This is third slide
   image: '/slides/images/wallachia.png'
   

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
