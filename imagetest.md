---
layout: default
published: true
---
<p>
  {% for page in site.pages %}
          {% if page.image %}
            
            <img class="col" src="/img/{{ page.image }}" alt="" /></div>
          {% endif %}
        {% endfor %}  
  </p>
