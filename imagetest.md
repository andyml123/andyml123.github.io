---
layout: default
published: true
---
<p>When a friend or loved one is ill the thing we want most is for them get well soon. We may not be able to help speed up their recovery but we can let them know they're in our thoughts. So sending a gift and card with a touching or inspirational get well message is the least we can do. </p>

<p>
Adsense ad here
</p>

<p>
Here you will find the best get well soon wishes and quotes. They will express your desire for a sick friend or relative to feel better soon, hoping for their speedy recovery. When you're feeling unwell a message from a friend can be a real boost and lift your spirits when you're feeling down.</p>

<p>
 
  {% for page in site.pages %}
          {% if page.image %}
   <h2><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
            <a href="{{ page.url | prepend: site.baseurl }}"> <img class="img" src="/img/{{ page.image }}" alt="" /></a>

          {% endif %}
        {% endfor %}  
  
  </p>
<hr>

{% for page in site.pages %}
    {% if page.image %}
 <div class="contentTop">
          <h2><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
          <a href="{{ page.url | prepend: site.baseurl }}"> <img class="img1" src="/img/{{ page.image }}" alt="" /></a>
          </div>
          {% endif %}
        {% endfor %}
