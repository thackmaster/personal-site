---
layout: page
show_meta: false
title: "Thoughts"
subheadline: "Category"
#header:
   #image_fullwidth: "header_unsplash_5.jpg"
permalink: "/thoughts/"
---
<ul>
    {% for post in site.categories.thoughts %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>