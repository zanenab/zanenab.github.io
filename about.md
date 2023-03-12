---
layout: page
title: About
permalink: /about
---

I am called Will. 


[About](https://zanenab.github.io/test.html)


ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
