---
layout: page
title: Archivo
permalink: /archive/
---

Aquí guardo todas las batallas pasadas, ordenadas cronológicamente.

{% for post in site.posts %}
  {% capture day %}{{ post.date | date: '%d' }}{% endcapture %}
  {% capture month %}{{ post.date | date: '%m' }}{% endcapture %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  
  {% if year != prev_year %}
    ### {{ year }}
    {% assign prev_year = year %}
  {% endif %}

  * {{ post.date | date: "%b %d" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}
