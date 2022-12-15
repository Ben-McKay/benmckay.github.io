---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

{% include base_path %}

{% for post in site.papers reversed %}
  {% include archive-single.html %}
{% endfor %}

My papers are [here](https://arxiv.org/search/?query=mckay_b_1&searchtype=all&source=header) on the arxiv.
