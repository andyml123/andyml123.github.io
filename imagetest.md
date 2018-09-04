---
layout: default
published: true
---
<p>
 
  {% for page in site.pages %}
          {% if page.image %}
   <h2><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
            <a href=href="{{ page.url | prepend: site.baseurl }}" img class="img" src="/img/{{ page.image }}" alt="" />

          {% endif %}
        {% endfor %}  
  
  </p>
