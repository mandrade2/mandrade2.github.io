---
layout: default
---
# Posts
<div class="post-list">
<ul >
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
</div>