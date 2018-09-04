---
layout: default
published: true
---
<p>
  {% for page in site.pages %}
          {% if page.image %}
            <div class="home-columns"><h2><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
            <img class="col" src="/img/{{ page.image }}" alt="" /></div>
          {% endif %}
        {% endfor %}  
  </p>
