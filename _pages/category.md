---
title: "categories"
layout: categories
permalink: /categories
author_profile: true
sidebar:
    nav: "sidebar-category"
---


{% assign posts = site.categories %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}