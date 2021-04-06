---
layout: default
title: history
---

<ol class="monospace" reversed>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span class="mini">{{ post.date | date: "%D" }} {{ post.time }}</span>
    </li>
    {% endfor %}
</ol>