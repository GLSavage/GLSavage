---
layout: default
title: ""
---

<img src="{{ site.baseurl }}/SavageLogo.png" alt="" style="width:80px; margin-bottom:16px;">

<h2 style="font-size:1.6rem; font-weight:500; margin-top:0;">
  Something you saw brought you here. 
</h2>

<p style="margin-top:24px;">
  <a href="https://payhip.com/GLSavage"
     style="font-size:1.2rem; font-weight:600;">
    This is the work behind it.
  </a>
</p>


<hr>

{% include products.html %}
<h2>Recent articles</h2>

{% if site.posts and site.posts.size > 0 %}
<ul>
  {% for post in site.posts limit:5 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a><br>
    <span>{{ post.excerpt | strip_html | truncate: 260 }}</span><br>
    <a href="{{ post.url | relative_url }}">Read more</a>
  </li>
  {% endfor %}
</ul>
{% else %}
<p>No articles yet.</p>
{% endif %}
[More articles]({{ "/articles.html" | relative_url }})



## About

G. L. Savage writes about control, compliance, and the structural pressures shaping modern life.  
This work is not motivational or therapeutic. It examines how systems limit choice and what it takes to reclaim autonomy.

[Optional support here](https://ko-fi.com/glsavage) helps make continued writing and publishing possible.


