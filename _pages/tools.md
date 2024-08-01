---
layout: archive
title: "Tools"
permalink: /tools/
author_profile: true
---

{% include base_path %}

<p style="color:#888888;"><i>JetBrains Research develops a lot of useful 
practical tools for various software engineering purposes. Some of these tools support research, some are meant
for the end-users. This page aims to list all of our main tools.</i></p>

{% for post in site.tools %}
{% include archive-single.html %}
{% endfor %}