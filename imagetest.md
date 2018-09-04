---
layout: default
published: true
---
<p>
<div class="side-by-side">
  {% for page in site.pages %}
          {% if page.image %}
          <h2><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
            <img class="img" src="/img/{{ page.image }}" alt="" />
          {% endif %}
        {% endfor %}  
        </div>
        <div class="side-by-side">
        
        {% for page in site.pages %}
          {% if page.image %}
        
        <img class="img" src="/img/{{ page.image }}" alt="" width="50" height="50" />
        
        {% endif %}
        {% endfor %}  
        </div>
  </p>
