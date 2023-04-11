---
title: "Spring"
layout: categories
permalink: /categories/annotation/
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.annotation %}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}