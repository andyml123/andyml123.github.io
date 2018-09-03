---
layout: default
published: true
---

Testing...

<div class="home">

  TESTING THIS
  
  {% for page in site.pages %}
          {% if page.image %}
          <img src="/img/{{ page.image }}" alt="" />
            <h2><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
         
          {% endif %}
        {% endfor %}  
  
</div>
