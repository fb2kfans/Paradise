---
layout: page
title: Hello World!
tagline: Explore Everything
---
{% include JB/setup %}

记录遇到的问题，以作参考。

记录总结经验。

学习和分享。

## Recent Posts

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
