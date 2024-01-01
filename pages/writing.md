---
layout: page
show_meta: false
title: "Writing"
subheadline: "Category"
#header:
   #image_fullwidth: "header_unsplash_5.jpg"
permalink: "/writing/"
---
<ul>
    {% for post in site.categories.writing %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>