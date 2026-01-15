---
title: About Me
layout: single
author_profile: true
---

## Hi 👋

I’m **TMEERS**, a Site Reliability Engineer focused on building
reliable, automated, and scalable systems.

### What I work with
- 🐧 Linux & networking
- ☸ Kubernetes & containers
- ⚙️ CI/CD pipelines
- 📈 Monitoring & observability

---

## Latest Posts

{% assign latest_posts = site.posts | slice: 0, 3 %}
{% for post in latest_posts %}
### [{{ post.title }}]({{ post.url }})
{{ post.excerpt | strip_html | truncate: 140 }}
{% endfor %}
---
