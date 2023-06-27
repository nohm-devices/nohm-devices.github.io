---
layout: page
title: Home
description: "Nohm Devices: novel ultra-low-power electronics leveraging non-Ohmic transport"
permalink: /
---

Coming soon ...

## News

{% for post in site.posts limit:3 %}
+ {{ post.date | date: "%b %-d, %Y" }}: [ {{ post.title }} ]( {{ post.url | prepend: site.baseurl }} )
{% endfor %}
+ [Older news](/news/)
