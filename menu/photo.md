---
layout: page
title: Photo
---
<ul class="posts">
  {% for photo in site.data.settings.photoImgs %}
    <li itemscope>
      <img src="/assets/img/{{ photo.src }}"/>
    </li>
  {% endfor %}
</ul>
