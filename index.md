---
layout: default
---

Hello from index

<div>
  {% for post in site.posts limit: 3 %}
    <a href="{{post.url}}">{{ post.title }}</a>
    <div>
      {{ post.content }}
    </div>
  {% endfor %}
</div>
