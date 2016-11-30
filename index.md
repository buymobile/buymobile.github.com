---
layout: post
title:  "程成的静态博客"
date:   2016/11/30 10:12:23
categories: original test html5 php js css3
---

<!-- lang: html -->

{% for post in site.posts %}

{{ post.date|date_to_string }} <a href='{{ site.baseurl }}{{ post.url }}'>{{ post.title }}</a>

{% endfor %}
