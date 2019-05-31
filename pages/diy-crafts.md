---
layout: page
show_meta: false
title: "DIY & Crafts Main Page"
subheadline: "DIY & Music Subheadline"
header:
    title: DIY-Crafts Title
    background-color: "#BB218C;"
permalink: /diy-crafts/

---

### All Related Blog Posts
{: .t60 }

{% include list-posts tag='header' %}

---

<ul>
    {% for post in site.categories.diy-crafts %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
