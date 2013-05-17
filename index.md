---
layout: default
title: Jekyll Boilerplate
---

This is the index page for the Jekyll Boilerplate.

### Blog Posts

<div id="posts">

    <ul class="posts">
        {% for post in site.posts %}
            <li><a href="{{ post.url }}">{{ post.title }}</a> - <span>{{ post.date | date_to_string }}</span></li>
        {% endfor %}
    </ul>

</div>
