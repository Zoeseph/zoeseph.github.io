---
layout: page
show_meta: false
title: "Autism Main Page"
subheadline: "Autism Subheadline"
header:
    title: Autism
    background-color: "#EFC94C;"
permalink: /autism/

---

## Resourceful links n shiz

* link 1
* link 2
* this too, is a link
* link 4


### All Related Blog Posts
{: .t60 }

{% include list-posts tag='header' %}

---

<ul>
    {% for post in site.categories.autism %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
