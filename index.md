---
layout: page
title: ricetuan's Blogs!
---
{% include JB/setup %}

{% for post in site.posts %}
## {{ post.title }}
  {{ post.excerpt }}
  <a href="{{ post.url }}">Read more...</a>

  <div style="text-align: right;">
    {{ post.date | date_to_string }}
  </div>

---------------------------------------
{% endfor %}
