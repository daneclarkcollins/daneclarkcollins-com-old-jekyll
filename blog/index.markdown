---
layout: page
status: publish
published: true
title: Automatic Writing
---

<ul>
{% for post in site.posts %}
    <li>
        <div class="date">{{ post.date | date_to_string }}</div>
        <a href="{{ site.prefix  }}{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
