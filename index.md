---
layout: default
title : Nate Neff
---

# Nate Neff\'s blog

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id
est laborum 

{% for post in site.posts %}
<div>
    <h2>{{ post.title }}</h2>
    <h4>{{ post.date | date_to_long_string }}</h4>
    <p>
        <a href="{{ post.url }}">Read Post</a>
    </p>
</div>
{% endfor %}
