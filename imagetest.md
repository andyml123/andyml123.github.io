---
layout: default
published: true
---
<p>
    <div class="side-by-side">
   
     {% for page in site.pages %}
       {% if page.image %}
        
    <img class="img" src="/img/{{ page.image }}" alt="" width="50" height="50" />
        
        {% endif %}
        {% endfor %}  
     </div>
  </p>
