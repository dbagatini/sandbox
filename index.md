---
layout: default
title: Blog
---
<h1>{{ page.title }}</h1>
<ul class="posts">
    {% for post in site.posts %}
        <li><span>{{ post.title }}</span></li>
    {% endfor %}
</ul>
