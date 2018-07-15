---
# Home page issue.
# Use title, number, and feature include for current issue.
title:  "frontiers"
number: 5
date:   2018-02-10 08:00:00 -0400
layout: default
---

# Stuff

{% for item in site.issues %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.content }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}
