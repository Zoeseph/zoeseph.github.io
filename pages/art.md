---
layout: page
show_meta: false
title: "Art Main Page"
subheadline: "Art Subheadline"
header:
    title: Art
    background-color: "#32FFCA;"
permalink: /art/

---

### All Related Blog Posts
{: .t60 }

{% include list-posts tag='header' %}

---

<ul>
    {% for post in site.categories.dumy %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
