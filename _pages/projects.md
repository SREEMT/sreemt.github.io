---
title: Projects
layout: collection
collection: projects   # <- must match your _projects folder
author_profile: true
sidebar:
  nav: resume_only
permalink: /projects/
---

## My Projects

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})
{{ project.excerpt | strip_html | truncate: 140 }}
{% endfor %}
