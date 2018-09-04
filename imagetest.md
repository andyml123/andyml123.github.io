---
layout: default
published: true
---
<p>
  {% for page in site.pages %}
          {% if page.image %}
          <div class="home-columns"><h2 class="index-titles"><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
            <img class="img" src="/img/{{ page.image }}" alt="" /></div>
          {% endif %}
        {% endfor %}  
        
        {% for page in site.pages %}
          {% if page.image %}
        
        <div class="side-by-side">
        <img class="img" src="/img/{{ page.image }}" alt="" />
        </div>
        
        {% endif %}
        {% endfor %}  
  </p>
