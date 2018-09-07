---
layout: default
published: true
---
<p>When someone close to us is unwell the thing we want most is for them get well soon. We may not be able to help speed up their recovery but we can let them know they're in our thoughts. So sending a gift and card with a touching or inspirational get well message is the least we can do. </p>

<p>
Adsense ad here
</p>

<p>
Here you will find the best get well soon wishes and quotes. They will express your desire for a sick friend or relative to feel better soon, hoping for their speedy recovery. When you're unwell a message from a friend can be a real boost and lift your spirits when you're feeling down.</p>

<div class="row">
  <div class="column">
<h2><a class="page-link" href="/get-well-wishes">Top 100 Get Well Wishes</a></h2>
<a href="/get-well-wishes"> <img class="img" src="/img/get-well-soon-wishes.png" alt="" /></a>
</div>

<div class="column">
<h2><a class="page-link" href="/get-well-soon-messages-for-a-friend">Get Well Soon Messages for a Friend</a></h2>
<a href="/get-well-wishes"> <img class="img" src="/img/get-well-soonmessages-for-a-friend.png" alt="" /></a>
</div>
</div>

<p>
You might prefer to post something on Facebook or Twitter, where sharing get well soon quotes for friends is often done. It's a good way to let lots of people offer their messages and best wishes for the sick to get better soon.
</p>

<p>
And if you know the person well who's ill or injured then you can consider using a funny get well message. Putting a smile on the face of or giving a laugh to those who are unwell can be a great way to make them feel a little better. 'Laughter is the greatest medicine', as they say!
</p>

<p>
<h2><a class="page-link" href="/get-well-soon-quotes/">Get Well Soon Quotes: 46 Touching and Uplifting Recovery Quotes</a></h2>
<a href="/get-well-wishes"> <img class="img" src="/img/get-well-soon-quotes.png" alt="" /></a>
</p>

<p>
<h2><a class="page-link" href="/get-well-wishes">Funny Get Well Soon Wishes and Messages</a></h2>
<a href="/funny-get-well-soon-wishes"> <img class="img" src="/img/funny-get-well-wishes.png" alt="" /></a>
</p>

<p>
We understand writing a get well message can be tricky. You want your words to make those ill feel better, to lift their mood, and express exactly what they mean to you. Rest assured that a get well card or gift will be warmly received by those recovering. And as long as you're sincere and speak from the heart whatever you say will be greatly appreciated. But if you're still unsure then try our guide to writing the perfect get well message.
</p>

<p>
If you're going to see the ill person at home or in hospital, or you want something to go with your get well card, a small gift is a good option. Choosing the right present can be tough though. Try our get well gift ideas or top get well gifts to help make that decision easier.
</p>

<div class="row">
  <div class="column">

<h2>What to Say in a Get Well Card</h2>
<p>
Not being confident about writing a get well message is common. You may be unsure of the best words to use or having trouble expressing exactly what the ill friend or loved one means to you.
</p>
<ul class="tick">
<li>Wishing you a full and speedy recovery</li>
<li>My thoughts and prayers for you to feel better soon</li>
<li>Sending love and positive thoughts your way. Get better soon!</li>
<li>Wishing you to feel better every day</li>
<li>Hoping you feel better very soon and I can't wait to see you again</li>
</ul>

</div>
 
<div class="column"> 
<h2>What NOT to say in a Get Well Card</h2>
<p>
There are a few things you should absolutley avoid saying in your get well soon message. These phrases and choice of words could upset or cause the recipient to feel even worse.
</p>
<ul class="cross">
<li>Don't be negative. Stay upbeat and use encouraging words to make them feel more positive</li>
<li>Don't act or talk differently. They will want you to be as normal as possible with them. So write to them as you usually would</li>
<li>Don't be too religious in your message unless you know they will appreciate it. If you're in any doubt then err on the side of caution and stick with a regular message</li>
<li>Don't mention death! This should be obvious but all you will do is terrify and them. Avoid any mention of their mortality.</li>
<li>Don't use phrases like "everything happens for a reason" or "God has a plan". These sorts of sentiments can be offensive and not what someone who is ill will want to hear.</li>
</ul>  
</div>
</div>

<p>
 
  {% for page in site.pages %}
          {% if page.image %}
   <h2><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
            <a href="{{ page.url | prepend: site.baseurl }}"> <img class="img" src="/img/{{ page.image }}" alt="" /></a>

          {% endif %}
        {% endfor %}  
  
  </p>
<hr>
<div class="row">
{% for page in site.pages %}
    {% if page.image %}
 <div class="column">
          <h2><a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
          <a href="{{ page.url | prepend: site.baseurl }}"> <img class="img" src="/img/{{ page.image }}" alt="" /></a>
          </div>
          {% endif %}
        {% endfor %}
</div>

<hr>

{% for page in site.pages limit:6 %}
  {% if apage.url != page.url %} 
    {% if forloop.index < 6 or found %}
 <h3>
 <a href="{{ page.url }}">{{ page.title }}</a>
 </h3>
    {% endif %}
  {% else %}
    {% assign found = true %} 
  {% endif %}
{% endfor %}

<hr>

  {% for apage in site.pages %}
    {% if apage.categories == 'messages' %}
        {% if page.url != apage.url %}
            <ul>
                <li><a href="{{ apage.url }}">{{ apage.title }}</a></li>
            </ul>                                               
        {% endif %}
    {% endif %}
{% endfor %}

<hr>

{% for onepage in site.pages %}
  {% if page.categories contains 'messages' %}
{% unless page.id == onepage.id %}
 <h3>
 <a href="{{ page.url }}">{{ page.title }}</a>
 </h3>
{% endunless%}
{% endif %}
{% endfor %}
