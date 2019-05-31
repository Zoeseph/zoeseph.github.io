---
layout: page
show_meta: false
title: "Tech Main Page"
subheadline: "Tech Subheadline"
header:
    title: Tech
    background-color: "#3CE92E;"
permalink: /tech/

---

### All Related Blog Posts
{: .t60 }

{% include list-posts tag='header' %}

---

<ul>
    {% for post in site.categories.tech %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
