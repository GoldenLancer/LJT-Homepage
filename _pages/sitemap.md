---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
sitemap: false
---

{% include base_path %}

## Pages

- [Home]({{ base_path }}/)
- [Publications]({{ base_path }}/publications/)

## Publication Pages

<ul>
  {% assign sorted_publications = site.publications | sort: "pub_order" %}
  {% for post in sorted_publications %}
    <li><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
