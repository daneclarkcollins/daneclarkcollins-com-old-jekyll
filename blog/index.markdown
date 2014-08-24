---
layout: page
title: Just Words
---

<ul>
{% for post in site.posts %}
    <li>
        <a href="{{ site.prefix  }}{{ post.url }}">{{ post.title }}</a>
        <div class="date">{{ post.date | date_to_string }}</div>
        {{ post.excerpt }}
    </li>
{% endfor %}
</ul>
