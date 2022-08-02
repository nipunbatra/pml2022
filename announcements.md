---
layout: page
title: Assignments
nav_exclude: true
description: A feed containing all of the class assignments.
---

# Assignments

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
