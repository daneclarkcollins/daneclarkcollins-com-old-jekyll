---
layout: page
title: Welcome!
handle: homepage
description: Dane Clark Collins is a writer of speculative fantasy and sci-fantasy fiction and and experimental musician from Philadelphia, PA.
ogtype: website
---

## Latest Release: The Crossroads of the Never: Book 1

<div class="book cover left">{% include ads/crossroads-of-the-never-cover-box.html %}</div>

For Toryn Ninefingers, this is almost like any other night, entertaining a rowdy crowd with song and story. But tonight, he has a special purpose in the telling of his tale, and reveals a shocking personal story that he has never told an audience before. With its telling, the world of Uteria may never be the same again.

This is the first book in the Crossroads of the Never saga, a series spanning thousands of years, shedding light on the dark and disturbing mysteries of the world of Uteria—a world besieged by the passing of a dark age, the continuing echoes of its violent history, and the recent incursion of creatures long since forgotten.

<a href="/crossroads-of-the-never/book-1/" class="button" title="The Crossroads of the Never: Book 1">Learn more...</a>

## Latest Posts

{% for post in site.posts limit:5 %}
<h4 style="margin-bottom:0"><a href="{{ site.prefix  }}{{ post.url }}">{{ post.title }}</a></h4>
<p style="margin-bottom:0;color:#999;font-style:italic;">{{ post.date | date_to_string }}</p>
{% if post.custom_excerpt %}
{{ post.custom_excerpt }}
{% else %}
{{ post.excerpt }}
{% endif %}
{% endfor %}

<a href="/blog/" class="button" title="Dane Clark Collins Blog">More posts...</a>
