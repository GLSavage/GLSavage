---
layout: default
title: ""
---

<img src="{{ site.baseurl }}/SavageLogo.png" alt="" style="width:120px; margin-bottom:16px;">

<p>Something you saw brought you here.</p>

<p><a href="PAYHIP_URL_HERE">View the work</a></p>

<hr>

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

<p><a href="{{ '/writing/' | relative_url }}">More articles</a></p>

