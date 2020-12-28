---
layout: page
title: Cakes 
permalink: /cake/
---
Back in February I got a crazy cake lady look in my eye and declared I was going to make every cake in Grandma Rose's book of Sinfully Delicious cakes, cookies, and desserts.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
