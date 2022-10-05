---
title: "Test"
layout: archive
permalink: /categories/test
author_profile: true
sidebar:
    nav: "sidebar-category"
---


{% assign posts = site.categories.Test %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}