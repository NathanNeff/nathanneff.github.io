---
layout: default
title : Nate Neff
---

{% for post in site.posts %}
<div>
    <h2>{{ post.title }}</h2>
    <h4>{{ post.date | date_to_long_string }}</h4>
    <p>{{ post.excerpt }}</p>
    <p>
        <a href="{{ post.url }}">Read Post</a>
    </p>
</div>
{% endfor %}
