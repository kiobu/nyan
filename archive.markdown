---
layout: aesthetic/aesthetic
title: Archive
---
<section>
    <p>
  {% for post in site.posts %}
      <a href="{{ post.url }}">{{ post.date | date_to_long_string }} —
      {{ post.title }}</a> <br>
  {% endfor %}
    </p>
</section>