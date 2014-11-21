---
layout: page
title: Welcome!
handle: homepage
description: Dane Clark Collins is a writer of speculative fantasy and sci-fantasy fiction and and experimental musician from Philadelphia, PA.
ogtype: website
---

## Latest Release: The Elves of Uteria

<div class="book cover left"><img src="/media/covers/the_elves_of_uteria.jpg" alt="The Elves of Uteria"><br />The Elves of Uteria<br><span class="small-text">Buy: <a href="http://www.amazon.com/gp/product/0996013806/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=0996013806&linkCode=as2&tag=danclacol-20&linkId=BOIDDFLR76RZBL27" target="_blank">Amazon</a><br>Buy: <a href="http://rpg.drivethrustuff.com/product/128540/The-Elves-of-Uteria?affiliate_id=646556" target="_blank">DriveThruRPG</a></span></div>

The Elves of Uteria is a story heavy source book featuring an original re-imagining of fantasy elves. The book is 76 pages with plenty of art, fiction and gaming material.

The Elves of Uteria is told through the eyes of Jarin Plainswalker, as Druid from the Western Council who was tasked with reestablishing contact with the elves of the world. The five different cultures of the elves are explored, as well as the elflings, who are the fey cousins of the elves.

Jarin keeps records of the places he goes, so the book includes a map of western Uteria, Jarin’s journals and entries as he travels, and some of the creatures he encounters.

Magic has also begun to wake in the lands, and Jarin records the different types he encounters and their application in the world around him.

<a href="/world-of-uteria/the-elves-of-uteria/" class="button" title="The Elves of Uteria">Learn more...</a>

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
