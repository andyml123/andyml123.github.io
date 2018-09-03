---
layout: default
published: true
---
<p>
  {% for page in site.pages %}
          {% if page.image %}
            <h2><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
            <img class="center" src="/img/{{ page.image }}" alt="" width="200" height="200" />
          {% endif %}
        {% endfor %}  
  </p>
