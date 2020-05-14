---
layout: default
---

[LastFM Bot](https://life-termer.github.io/LastFMBot/)
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
