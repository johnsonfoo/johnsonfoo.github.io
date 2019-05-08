---
title:  "Posts"
layout: archive
permalink: /posts/
author_profile: true
comments: true
---

{% for post in site.posts %}
    {% include archive-single.html %}
{% endfor %}