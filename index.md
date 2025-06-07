---
layout: default
---

## Here are all posts:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">[{{post.tags[0]}}] {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
