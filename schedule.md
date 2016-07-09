---
layout: page
title: Schedule
language: en
permalink: /schedule/
icon: /assets/icons/calendar.svg
---

<div class="home">
  <ul class="post-list">
    {% for post in site.posts reversed %}
    {% if post.language == "en" %}
      <li>
        {{ post.content }}
      </li>
    {% endif %}
    {% endfor %}
  </ul>
</div>

