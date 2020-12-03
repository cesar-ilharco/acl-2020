---
title: Conference Blog
layout: archive
permalink: /blog/
author_profile: false
sidebar: false
read_time: false
share: true
comments: false
---

Based on the positive reception of the blogs for 
the ACL 2020 conferences, the ACL 2021 website

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
