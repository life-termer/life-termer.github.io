---
layout: default
---

[LastFM Bot](https://life-termer.github.io/LastFMBot/)

[Minesweeper Game](https://life-termer.github.io/Minesweeper/)


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
