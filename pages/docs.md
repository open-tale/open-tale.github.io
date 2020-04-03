---
layout: page
title: Documentation
permalink: /docs/
---

# Documentation

The Open Tale documentation is organized in chapters disposed in a didactic
order:

<div class="section-index">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
