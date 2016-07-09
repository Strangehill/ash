---
layout: default
language: zh
english_permalink: /
---



<div class="home">

  <ul class="post-list">
    {% for post in site.posts reversed %}
    {% if post.language == "zh" %}
      <li>
        {{ post.content }}
      </li>
    {% endif %}
    {% endfor %}
  </ul>

</div>

