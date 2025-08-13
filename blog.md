---
layout: default
title: Blog
---

<div class="container">
    <h1 style="text-align: center; margin-bottom: 2rem; color: #333;">Latest Blog Posts</h1>
    
    <div class="blog-grid">
        {% for post in site.posts %}
        <article class="blog-post">
            <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
            <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
            <div class="date">{{ post.date | date: "%B %Y" }}</div>
        </article>
        {% endfor %}
    </div>
</div>